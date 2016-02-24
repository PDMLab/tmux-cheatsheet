# tmux cheat sheet for Ubuntu

#General
[tmux](https://tmux.github.io/) is a terminal multiplexer and allows you to split your terminal window into multiple panes or having multiple windows.
Furthermore it supports sessions, but these are not described in the cheat sheet.

#Installation

```
sudo apt-get update
sudo apt-get install tmux
```

#Running tmux

```tmux``` can be run from within an terminal window by typing ```tmux```

#Commands

```tmux``` commands are introduced by hitting ```<CTRL>+b``` followed by the command.

#Windows

```<CTRL>+b c``` creates a new ```tmux``` window    
```<CTRL>+b ,``` rename a window     
```<CTRL>+b p``` previous window    
```<CTRL>+b n``` next window    
```<CTRL>+b w``` list window / select    

#Panes

```<CTRL>+b %``` split window (create pane) vertically    
```<CTRL>+b : split-window``` split window (create pane) horizontally     
```<CTRL>+b o``` next pane     
```<CTRL>+b x``` exit pane     
```<CTRL>+b q<number>``` access pane by number, e.g. ```<CTRL>+b q1```     
```<CTRL>+b [``` enable scrolling history in current pane (use mouse or ```pgUp``` / ```pgDown```)     
```q``` leave scroll view in pane

```<CTRL>+b : resize-pane -D``` Resize the current pane down    
```<CTRL>+b : resize-pane -U``` Resize the current pane up    
```<CTRL>+b : resize-pane -L``` Resize the current pane left   
```<CTRL>+b : resize-pane -R``` Resize the current pane right   
```<CTRL>+b : resize-pane -D 10``` Resize the current pane down by 10 cells   
```<CTRL>+b : resize-pane -U 10``` Resize the current pane up by 10 cells   
```<CTRL>+b : resize-pane -L 10``` Resize the current pane left by 10 cells   
```<CTRL>+b : resize-pane -R 10``` Resize the current pane right by 10 cells   

