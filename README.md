Install
=======

git clone https://github.com/elm/config-files
shopt -s dotglob nullglob
mv config-files/* .
mv .git .home.git
chsh -s /bin/zsh elm
homegit submodule update --init .vim/bundle/vundle

