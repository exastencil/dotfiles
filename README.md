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

## Tools I use

- [Oh My Zsh](https://ohmyz.sh) for a friendlier shell
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k) for better shell awareness
- [tmux](https://github.com/tmux/tmux) for multiplexing

- [Vim](https://www.vim.org) for editing files
- [Lynx](https://lynx.invisible-island.net) for browsing the web

- [asdf](https://asdf-vm.com) for language version management

- [Ruby](https://www.ruby-lang.org) for scripting and web development
- [Go](https://golang.org) for scripting and web development
- [V](https://vlang.io) for scripting and web development
