# vim-setup - Ubuntu 17.10

1a. Install Powerline-Fonts

https://askubuntu.com/questions/283908/how-can-i-install-and-use-powerline-plugin

1b. You may also want to install the following packages :

`sudo apt-get install -y powerline powerline-fonts`

2. Copy `.vimrc` to `~`

3. [Install Vundle](https://github.com/VundleVim/Vundle.vim)

4. Run Vundle Plugin install

   1. Open vim `vim ~/.vimrc`
   2. Run the following commands...
   ```
   :source %
   :PluginInstall
   ```