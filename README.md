# i3-Project
shared i3 repo

# update everything
``apt-get update -y && apt-get upgrade -y && apt-get dist-upgrade -y
``
# Run following on commandline
``apt-get install i3
apt-get install i3lock
apt-get install rxvt-unicode
apt install nm-applet
apt install git
``

# Audio applet
``apt install pnmixer
``
# Wifi
`` apt install nm-applet
``
nm-tray & in config file.

# git clone files to your distro and move the config files to the correct place.
`` mv config .config/i3/config
mv .Xdefault /userfolder/.Xdefault
``

# background
``apt-get install feh``

# open an image with feh
``feh imagename.jpg
``
# set it as your background
``cat .fehbg
nano .xinitrc
``
# add this in the file:
``~/.fehbg
``
# close and save.
on reboot your background will now be taken from the .fehbg file.

# optional selenium drivers
*geckodirvers for selenium
*https://github.com/mozilla/geckodriver/releases
*export PATH=$PATH:/root/Downloads/geckodriver-v0.23.0-linux64
