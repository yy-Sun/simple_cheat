## CMake 基础模版

一个最基础的CMakeList.txt 需要以下信息

```cmake
# 最低cmake版本
cmake_minimum_required (VERSION 2.8)

# 项目命名
project (Demo1)

# 生成的可执行文件/生成库文件
add_executable(Demo main.cc)
```



## 对可执行文件的依赖扩展

可执行文件的原码为当前目录下

```cmake
add_executable(Demo main.cc math.c)
```

