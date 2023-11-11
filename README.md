# shutdown-nasm
### step 1 compiling the nasm file
```sh
 nasm -f elf64 shutdown.nasm -o shutdown.o
```

### step 2 linking 
```sh
ld shutdown.o -o shutdown
```

### step 3 run the cmd to turn it off
```sh
./shutdown
```
