# Linux上的x86組合語言設計

來源 -- https://cs.lmu.edu/~ray/notes/gasexamples/

Linux 系統呼叫表 -- https://blog.rchapman.org/posts/Linux_System_Call_Table_for_x86_64/

這些範例只能在 Linux 上跑

用 ssh 連上我的虛擬主機

網址: ssh guest@139.162.90.34
密碼: csie320

連上後請切到資料夾 ~/course/sp/code/c/03-asmVm/asm/linux

之後就可以執行範例，例如 hello.s

先切到 01-hello

```
$ gcc -c hello.s
$ ld hello.o -o hello
$ ./hello
Hello, world
```

## 參考


* https://cs.lmu.edu/~ray/notes/x86assembly/
* http://www.egr.unlv.edu/~ed/assembly64.pdf
* https://github.com/Apress/beginning-x64-assembly-programming