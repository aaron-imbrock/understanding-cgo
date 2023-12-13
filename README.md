# understanding-cgo
Exercises in creating C functions, and calling them from Go

## Issues

```bash
? ~/go/src [main|?5] 
16:52 $ ls
go.mod  greeter.c  greeter.h  greeter.o  main.go  README.md
? ~/go/src [main|?5] 
16:52 $ go install
# understanding-cgo
./main.go:18:8: could not determine kind of name for C.free
./main.go:25:10: could not determine kind of name for C.greet

? ~/go/src [main|?] 
16:59 $ ls -l
total 24
-rw-r--r-- 1 aimbrock aimbrock   36 Dec 13 14:58 go.mod
-rw-r--r-- 1 aimbrock aimbrock  192 Dec 13 14:54 greeter.c
-rw-r--r-- 1 aimbrock aimbrock   97 Dec 13 14:55 greeter.h
-rw-r--r-- 1 aimbrock aimbrock 1568 Dec 13 14:55 greeter.o
-rw-r--r-- 1 aimbrock aimbrock  426 Dec 13 16:53 main.go
-rw-r--r-- 1 aimbrock aimbrock   80 Dec 13 14:51 README.md
? ~/go/src [main|?] 
16:59 $
```
