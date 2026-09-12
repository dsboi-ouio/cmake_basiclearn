# cmake_basiclearn

一个用于学习 CMake 基础用法的简单 C++ 项目，演示如何使用 CMake 组织多文件项目。

## 项目结构

```text
cmake_basiclearn/
│
├── CMakeLists.txt               # CMake 构建配置
│
├── includes/                    # 头文件
│   └── hello.hpp                # Hello 类声明
│
├── src/                         # 主程序源码
│   └── cmake_basiclearn.cpp     # 程序入口
│
└── tools/                       # 功能模块源码
    └── hello.cpp                # Hello 类实现
```