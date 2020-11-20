# Arch-Config


## archlinuxcn

sudo vim /etc/pacman.conf

[archlinuxcn]

Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch

sudo pacman -Syu archlinuxcn-keyring

## spacemacs

git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d


## vim

git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime

sh ~/.vim_runtime/install_awesome_vimrc.sh


## software

sudo pacman -S
screenfetch
firefox 
cmus
mousepad
fcitx fcitx-config-tool
emacs
mpv
ttf-dejavu
wqy-microhei

# touchpad

sudo vim /etc/X11/xorg.conf.d/30-touchpad.conf

Option "Natural Scrolling" "true"
