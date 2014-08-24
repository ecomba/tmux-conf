# My tmux configuration

The other day I was trying to teach a friend some [tmux](http://tmux.sourceforge.net)
and remote pairing over [tmate](http://tmate.io) and I discovered to my 
horror that I had lost all my [tmux](http://tmux.sourceforge.net) 
configuration files.

This is a way to remedy it in the future ( _and in general a good idea so that I can have my configuration saved in a place where it can evolve over time_ ).

## Installation

- In order to make this work you have to install [tmux](http://tmux.sourceforge.net)
first ( _if you have a Mac I do recommend using **brew install tmux** as it will ease your life_ ).
- Create a symbolic link in your home directory: 
```
ln -s path_you_cloned_this_repo/tmux.conf ~./.tmux.conf
```
