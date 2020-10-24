# dotfiles
System configuration files

This repository holds dotfiles that I use to configure my system. It follows
the [convention](https://www.atlassian.com/git/tutorials/dotfiles) of tracking
files directly in your `$HOME` directory with git bare directory named 
`.dotfiles` instead of `.git`. This is then accessed by an alias 
(`dot` instead of `git`) defined in the shell, e.g.

```
 dot add .bashrc
 dot status
 dot commit -m "Add .bashrc"
 dot push origin master
```
