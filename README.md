# pirate-arch-repo

my arch linux repo

# Add pirate-arch-repo to pacman

1- open /etc/pacman.conf with your text editor as root
2- add the following to the end of pacman.conf
```
[pirate-arch-repo]
SigLevel = Optional DatabaseOptional
Server = https://raw.githubusercontent.com/AbdelrhmanNile/pirate-arch-repo/main/x86_64
```
then save <br />
3- update pacman databases [and your packages, do not do partial updates]
```
sudo pacman -Syyu
```
