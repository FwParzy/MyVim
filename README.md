# MyVim  
My custom vim profile  
  
The main vimrc might need some adjusting for mac vs win  
  
To install tmux :  
$ Brew install tmux  
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm  
Open Tmux and do ctrl-a + I  
  
To Install Vim :  
Open Vim and do :PlugInstall  
Should be good? idk been a while since i set it up. Will add extra steps for more robust plugins  

To Install NeoVim :  
brew install neovim  
cd ~/.config/nvim  
ln -s ../../MyVim/init.vim init.vim  
:PlugInstall  
:source $MYVIMRC // might need to do this 2 times for gruvbox  
