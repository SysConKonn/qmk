## qmk 
AUTHOR: SysCon
## 主要作用
使编译cpp文件并且执行从文件输入变得快捷。
## 安装方法
+ 根据自己的sh版本选择安装文件。
+ 在终端打开下载文件目录。
+ 执行`./setup_ `... 指令。
+ 安装完成
## 使用方法
+ 在工作目录打开终端。
+ 我们假设当前需要编译的cpp文件为`demo.cpp`，需要从文件`demo.in`输入数据。
+ 在终端中输入命令`qmk demo.cpp demo.in`。
+ 此时当前目录下会多出编译后的文件`a.out`和程序通过`demo.in`读入数据后的输出文件`out`，同时在终端输出运行结果