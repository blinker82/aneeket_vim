* Instructions to use this repo ( bash )

* Make sure you have git installed.
* Then run the following or just clone it 
`git clone https://github.com/blinker82/aneeket_vim.git`

* Install vim ( I have only tested this with vim-gnome)
`sudo apt-get install vim-gnome`
( On Ubuntu version greater than 10 vim-gnome works but gives annoying errors like : 
(gvim:4054): GLib-GObject-WARNING **: Attempt to add property GnomeProgram::sm-connect after class was initialised

(gvim:4054): GLib-GObject-WARNING **: Attempt to add property GnomeProgram::show-crash-dialog after class was initialised

(gvim:4054): GLib-GObject-WARNING **: Attempt to add property GnomeProgram::display after class was initialised

(gvim:4054): GLib-GObject-WARNING **: Attempt to add property GnomeProgram::default-icon after class was initialised`
So to fix it.
sudo apt-get -y remove vim-gnome
sudo apt-get install vim-gtk )
Also rename aneeket_vim to .vim_runtime in root
`ln -s ~/.vim_runtime/vimrc_wrapper ~/.vimrc`
* Needed for tagging files
`sudo apt-get install exuberant-ctags`
* Also should install global 
 To update the git submodule packages which this vim config uses
`git submodule update --init`

------

* whenever you want updates just run the following
`git pull origin master`
