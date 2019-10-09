# i3-Project
shared i3 repo

# update everything
```

apt-get update -y && apt-get upgrade -y && apt-get dist-upgrade -y

```

# Run following on commandline
```

apt-get install i3
apt-get install i3lock
apt-get install rxvt-unicode
apt install nm-applet
apt install i3blocks
apt install git


```


# Audio applet
```

apt install pnmixer

```


# Wifi
```

apt install nm-applet

```

nm-tray & in config file.

# htop en iftop
sudo apt-get install iftop

# newsboat
snap install newsboat

# git clone files to your distro and move the config files to the correct place.
```

mv config .config/i3/config
mv .Xdefault /userfolder/.Xdefault

```


# background
```

apt-get install feh

```
open an image with feh
```

feh imagename.jpg

```

set it as your background
```

cat .fehbg
nano .xinitrc

```

add this in the file:
```

~/.fehbg

```
close and save.
on reboot your background will now be taken from the .fehbg file.


# Terminal colors:
based on https://github.com/altercation/solarized

![solarized palette](https://github.com/altercation/solarized/raw/master/img/solarized-palette.png)

![solarized vim](https://github.com/altercation/solarized/raw/master/img/solarized-vim.png)

```

Control-Shift-F3 for light terminal theme
Control-Shift-F4 for dark terminal theme

```


# optional for selenium users
geckodirvers for selenium
https://github.com/mozilla/geckodriver/releases
```

export PATH=$PATH:/root/Downloads/geckodriver-v0.23.0-linux64

```

