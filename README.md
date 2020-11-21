# Arch-Config

my config file for Manjaro(Arch) Linux 

- window manager: i3
- text editor: vim, emacs(spacemacs)
- terminal: urxvt
- web browser: firefox
- chinese input: fcitx shuangpin
- font: ttf-dejavu, wqy-microhei
- video player: mpv
- audio player: cmus
- file mamager: ranger, pcmanfm

## archlinuxcn

sudo vim /etc/pacman.conf

```
[archlinuxcn]

Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch
```

sudo pacman -Syu archlinuxcn-keyring

## spacemacs

git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d


## vim

git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime

sh ~/.vim_runtime/install_awesome_vimrc.sh

## touchpad

sudo vim /etc/X11/xorg.conf.d/30-touchpad.conf

```
Option "Natural Scrolling" "true"
```
