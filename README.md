# goodbye-world script 

### step 0 install nasm (varies from distributions-to-distributions)
```sh
 sudo pacman -S nasm
```

### step 1 compiling the nasm file
```sh
 nasm -f elf64 goodbye_world.nasm -o goodbye_world.o
```

### step 2 linking 
```sh
ld goodbye_world.o -o goodbye_world
```

### step 3 run the script
```sh
./goodbye_world
```
