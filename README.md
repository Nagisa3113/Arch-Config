# Arch-Config


## mirrors
vim /etc/pacman.d/mirrorlist

Server = https://mirrors.tuna.tsinghua.edu.cn/archlinux/$repo/os/$arch

## archlinuxcn
vim /etc/pacman.conf

[archlinuxcn]
SigLevel = Optional TrustAll
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch

sudo pacman -Syu archlinuxcn-keyring

## spacemacs
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d


## vim
git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime
sh ~/.vim_runtime/install_awesome_vimrc.sh


## software
sudo pacman -S

firefox
cmus
mousepad
fcitx fcitx-config-tool
emacs
mpv
ttf-dejavu
wqy-microhei

