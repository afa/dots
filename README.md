# dots
.dotfiles

# Standart install

``` sh
# FreeBSD
sudo portmaster sysutils/rcm
# lin
sudo apt-get install rcm
git clone git@github.com:afa/dots.git ~/.dotfiles
# optional
echo 'HOSTNAME="<some host name, rxists or new>" >> ~/.rcrc'
lsrc
rcup
```

# Install for ioteh workstation
```sh
rcup -B ioteh -g > ~/.dotfiles/install.sh
~/.dotfiles/install.sh
```

# TODO
Добавить .vim, плугины добавлять в репозиторий субмодулями, синхронизировать меж хостами. постхук?
Добавить .zsh. и .oh-my-zsh субмодулем
с afanote притащить ~/bin
