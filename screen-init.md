## Init Screen on Ubuntu

To initialize the screen on Ubuntu, you can use the following commands:

```
sudo apt update
sudo apt install screen
```

to init a new screen with name 

```
screen -S <screen_name>
```

to detach the screen

```
Ctrl + A + D
```

<!-- -x -->

to reattach the screen

```
screen -r <screen_name>
```

to list all screens

```
screen -ls
```

to kill a screen

```
screen -X -S <screen_name> quit
```
