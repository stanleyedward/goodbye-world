# shutdown-nasm
### step 1
```sh
 nasm -f elf64 shutdown.nasm -o shutdown.o
```

### step 2
```sh
ld shutdown.o -o shutdown
```

### step 3
```sh
./shutdown
```
