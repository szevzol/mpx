mpx
===

My terminal multiplexer configuration.

This repository serves as a portable configuration for me.
Feel free to use it but please beware of the fact that I didn't prepared it to be used by others.

Description
-----------

I use both tmux and screen.

On unix environment I use tmux, because I like its pane management and its nice client-server architecture.

On windows (mintty) environment I cannot use tmux, because it's simply not possible. So under mintty I use screen with the same look and feel as in tmux.

Install
-------

* Clone repo inside ~/etc. You will get a new directory ~/etc/mpx.

* For screen:
```sh
ln -s ~/etc/mpx/screenrc ~/.screenrc
```
* For tmux:
```sh
ln -s ~/etc/mpx/tmux.conf ~/.tmux.conf
```
