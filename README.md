### deps
`sudo yum install vim tmux zsh curl`

# vundle
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

# oh-my-zsh
`sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

# vim theme dir
`mkdir -p ~/.vim/colors`

# move
```
mv .tmux.conf ~/ &&
mv .vimrc ~/ &&
mv .zshrc ~/ &&
mv colors/ ~/.vim/
```

# vim plugin install
`vim +PluginInstall +qall`
