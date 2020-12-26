### Define Design Develop Automate
![](https://komarev.com/ghpvc/?username=coffeina&color=ee959e)

* Full Stack Engineer
* Rev Engineering
* DevOps
* Robotics
* InfoSec

## Get in touch

* Twitter: <https://twitter.com/AndrzejDubaj>
* LinkedIn: <https://www.linkedin.com/in/andrzejdubaj/>
* Blog: <https://www.handsonprogramming.io/>

``` asm
%define sys_write 1
%define stdout 1

%define sys_exit 60
%define success 0

%define nl 10

section .data

    message db "Hello, world!", nl
    message_len equ $-message

section .text

global _start
_start:
    mov rax, sys_write
    mov rdi, stdout
    mov rsi, message
    mov rdx, message_len
    syscall

    mov rax, sys_exit
    mov rdi, success
    syscall
```
