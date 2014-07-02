vimConfig
=========

My favorite vim configuration , and color scheme for c/c++.
Plugins are in the .vim directory.
Configuration is in the .vimrc file.

=======
1. Change vim to .vim
2. Change vimrc to .vimrc
3. cp c.vim to /usr/share/vim/vim74/syntax/
4. cp .vimrc to ~/
5. cp -r .vim to ~/
6. Install ctags:
  $ tar -xzvf ctags-5.6.tar.gz
  $ cd ctags-5.6
  $ make
  $ sudo make install  

Usage:
1.Ctags:
  Run ''ctags -R'' on the top of your project directory
  use command in VIM: set tags = \path\to\tags
2.WinManager:
  Type command in VIM: wm

Reference:
All Xterm256 coloar names for vim: http://vim.wikia.com/wiki/Xterm256_color_names_for_console_Vim
