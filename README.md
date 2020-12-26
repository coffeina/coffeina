# Define Design Develop Automate
![](https://komarev.com/ghpvc/?username=coffeina&color=ee959e)

* Full Stack Engineer
* Rev Engineering
* DevOps
* Robotics
* InfoSec

# Get in touch

* Twitter: <https://twitter.com/AndrzejDubaj>
* LinkedIn: <https://www.linkedin.com/in/andrzejdubaj/>
* Blog: <https://www.handsonprogramming.io/>

``` asm
section .rodata
    msg:    db 'hello, world', 10
    msglen: equ $-msg

section .text
    main:
        ; write(1, msg, msglen)
        mov rdi, 1
        mov rsi, msg
        mov rdx, msglen
        mov rax, 1
        syscall
```
