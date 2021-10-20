# ZEEEESHELLDOTARRSEEEEE

* Remember rule #1 and don't do [this](https://cdn-images-1.medium.com/max/2000/1*JR3-ExMjs20SbXwUmjI44g.png)
* Everything in `~/.zshrc`
* I **always** use zsh in tmux

## Keybindings ⌨️
I have them but the most import of them all is:
```
bindkey '^w' backward-kill-word
```

## Aliases
Yes ✅

## Completions
* `autoload -U compinit`
* Source whatever you need

## The prompt
* [Prompt Expansion](https://zsh.sourceforge.io/Doc/Release/Prompt-Expansion.html#Prompt-Expansion)
* `%~`
* `add-zsh-hook precmd mzc_termsupport_precmd` and `add-zsh-hook preexec mzc_termsupport_preexec`
* Updates tmux window titles

## Plugins
Checkout [github.com/zsh-users](https://github.com/zsh-users)

* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
* [zsh-completions](https://github.com/zsh-users/zsh-completions)
* [antigen](https://github.com/zsh-users/antigen)

## Other
* [fzf](https://github.com/junegunn/fzf)
* Derived from Manjaro 🐧

[Next Chapter - Git](06-git.md)