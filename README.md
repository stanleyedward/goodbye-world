# bye

### step 0 install nasm 
```sh
 sudo pacman -S nasm
```

### step 1 compile the nasm file
```sh
 nasm -f elf64 goodbye_world.nasm -o goodbye_world.o
```

### step 2 link 
```sh
ld goodbye_world.o -o goodbye_world
```

### step 3 run the script :D
```sh
./goodbye_world
```
