# ChCore

This is the repository of ChCore labs in OS course of SJTU CS3601, 2022 Fall.

Chcore实验共分为4个lab，依次完成环境搭建、机器启动、进程与线程创建、异常处理、多核多进程调度与进程间通信的代码实现。

`report`目录下为每个lab完成的实验报告。

## Build

- `make` or `make build`: Build ChCore
- `make clean`: Clean ChCore

## Emulate

- `make qemu`: Start a QEMU instance to run ChCore

## Debug with GBD

- `make qemu-gdb`: Start a QEMU instance with GDB server
- `make gdb`: Start a GDB (gdb-multiarch) client

## Grade

- `make grade`: Show your grade of labs in the current branch

## Other

- Press `Ctrl+a x` to quit QEMU
- Press `Ctrl+d` to quit GDB
