(1)使用前提：
安装好
1-cmake 
2-ninja 
3-arm-none-eabi-gcc 
4-arm-none-eabi-gdb
5-clangd

(2)本地移植（具体要修改的地方在该文件里都有注释提示）
1-修改工具链路径：在.vscode/settings.json中修改，具体地方看注释
2-修改工程名字：在工程根目录的cmakelists的14行修改工程输出的elf文件名字。在.vscode/launch.json里将elf文件名修改成你的elf文件名。在run.sh里将elf,bin,hex文件改成相应的文件名

(3)使用方法
直接在命令行终端运行./run.sh  or 快捷键 ctrl+alt+b