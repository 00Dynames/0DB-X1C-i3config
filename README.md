# 0DB-X1C-i3config
This is my i3 setup. (For X1 Carbon Gen 3) 

Powerline shell setup
```
sudo apt-get install powerline fonts-powerline
 
~ cat .bashrc
[..]
if [ -f `which powerline-daemon` ]; then
  powerline-daemon -q
  POWERLINE_BASH_CONTINUATION=1
  POWERLINE_BASH_SELECT=1
  . /usr/share/powerline/bindings/bash/powerline.sh
fi
```
