vimConfig
=========
My favorite vim configuration , and color scheme for c/c++.
Plugins are in the .vim directory.
Configuration is in the .vimrc file.

Installation
----
* Clone this repo in any directory.
* Change vim to .vim
* Change vimrc to .vimrc
* cp c.vim to /usr/share/vim/vim74/syntax/
* cp .vimrc to ~/
* cp -r .vim to ~/
* Install ctags:
```sh    
$ tar -xzvf ctags-5.6.tar.gz
$ cd ctags-5.6
$ ./configure
$ make
$ sudo make install  
```
Usage:
----
* 1.Ctags:
  * Run ''ctags -R'' on the top of your project directory
  * Type command in VIM: set tags = \path\to\tags
* 2.WinManager:
  * Type command in VIM: wm

Reference:
----
All Xterm256 color names for vim: http://vim.wikia.com/wiki/Xterm256_color_names_for_console_Vim

Chinese edition tutorial: http://blog.csdn.net/namecyf/article/details/7787479
