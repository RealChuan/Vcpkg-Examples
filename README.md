# Vcpkg

- [简体中文](README.md)
- [English](README.en.md)

## 介绍

这是一个关于使用vcpkg构建库的项目。

1. [vcpkg.yml](.github/workflows/vcpkg.yml)：使用actions自动化构建vcpkg中的依赖库；
2. [vcpkg.json](vcpkg.json)：使用`cmake`和`vcpkg`的`manifest`模式构建特定版本的依赖库，以openssl为例，[详细说明](https://realchuan.github.io/2023/11/29/Vcpkg-manifest-%E7%AE%80%E5%8D%95%E4%BB%8B%E7%BB%8D/)；
