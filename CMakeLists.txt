cmake_minimum_required(VERSION 3.25.1)

include(cmake/macOSDeploymentTarget.cmake)
include(cmake/VcpkgToolchain.cmake)

project(
  Vcpkg-Manifest
  VERSION 0.0.1
  LANGUAGES CXX)

include(cmake/CompilerSettings.cmake)

find_package(OpenSSL REQUIRED)
if(OpenSSL_FOUND)
  message(STATUS "found OpenSSL")
endif()

include(cmake/CMakeDebugInfo.cmake)
