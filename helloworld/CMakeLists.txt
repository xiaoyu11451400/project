#CMakeLists.txt

cmake_minimum_required(VERSION 3.0)
project(helloworld)

#编译配置选择"Debug"才能调试
set(CMAKE_BUILD_TYPE "Debug")
#set(CMAKE_BUILD_TYPE "Release")

#将helloworld.cpp生成helloworld可执行文件
add_executable(helloworld hello.cpp)