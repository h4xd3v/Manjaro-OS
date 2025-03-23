# Manjaro-OS
ISO: manjaro-xfce-24.2.1-241216-linux612.iso (Disk: 250) (RAM: 16) (CPU: P-4 PP-8)

## Mirrors
https://repo.manjaro.org/
https://wiki.manjaro.org/index.php/Pacman-mirrors

file: vi /etc/pacman.d/mirrorlist 
```bash
## Country : United_States
Server = https://opencolo.mm.fcix.net/manjaro/stable/$repo/$arch

## Country: Colombia
Server =  https://edgeuno-bog2.mm.fcix.net/manjaro/stable/$repo/$arch

## Country: Canada
Server = https://mirror.xenyth.net/manjaro/stable/$repo/$arch

```

# Update
```bash
$ sudo pacman -Syu
```

# yay
```bash
$ sudo pacman -S base-devel yay
```

t
