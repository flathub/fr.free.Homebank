# Homebank    

An unofficial flatpak version of Homebank.

## FAQ

- Network access

To enable access to the network use [flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal) or the command below.

```
flatpak override --share=network fr.free.Homebank
```

- File access

By default only access to xdg-documents is given. You can give homebank access to other files through 
[flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal) or with the command below.

```
flatpak override --filesystem=<PATH-TO-FILE/DIR> fr.free.Homebank
```
