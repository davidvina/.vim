# make symbolic link

#:checkhealth# symlink vim config
ln -s /Users/userName/.vim/.vimrc /UserName/david/

## symlink nvim config
ln -s /Users/david/.vim/nvim/ /Users/david/.config/


## Install nvim dependences python2 and python 3

https://ricostacruz.com/til/neovim-with-python-on-osx

### python

brew install python2
brew install python3

pip install neovim --upgrade
pip3 install neovim --upgrade

### Ruby
gem install neovim


### Node.js provider 
npm install -g neovim
