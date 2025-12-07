# 汇编项目合集
## syscall 目录
/usr/include/x86_64-linux-gnu/asm/unistd_64.h
## 汇编指令分区
data 和 text 区, 分别存放数据和指令
## 编译方式
```bash
sudo apt install nasm
nams -f elf64 -o xxx.o xxx.asm
ld -o xxx xxx.o
```
