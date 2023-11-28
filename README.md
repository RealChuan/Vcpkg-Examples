# Vcpkg

- [简体中文](README.md)
- [English](README.en.md)

## 介绍

这是一个关于使用vcpkg构建库的项目。

1. [vcpkg.yml](.github/workflows/vcpkg.yml)：使用actions自动化构建vcpkg中的依赖库；
2. [vcpkg.json](vcpkg.json)：使用`cmake`和`vcpkg`的`manifest`模式构建特定版本的依赖库，以openssl为例：
