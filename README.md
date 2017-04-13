# nwebl
Es un mini servidor web

Basado en https://www.ibm.com/developerworks/systems/library/es-nweb/index.html


## Clonar 
```
git clone https://github.com/robincoello/nwebl.git
```

## Copliar
```
cd nwebl
gcc -O -DLINUX main.c -o nwebl
```

## Ejecutar
```
 ./nwebl 8181 /home/robin/nwebl 

```

### ver resultado 
http://0.0.0.0:8181/index.html

# Para ver los procesos en ejecucion
```
ps

  PID TTY          TIME CMD
 3453 pts/0    00:00:00 bash
 4454 pts/0    00:00:00 nwebl
 4896 pts/0    00:00:00 ps

```

y ahora matar el proceso con kill

```
kill 44554

```
