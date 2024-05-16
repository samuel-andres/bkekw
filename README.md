[![Maintainer](https://img.shields.io/badge/maintainer-lebarondecharlus-blue)](https://github.com/samuel-andres)
[![MIT License](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit/)

<p align="center">
    <img src="./b.png" width="50%">
</p>

<center>
*bkekw is (an ugly, even uglier than [b](https://github.com/LeBaronDeCharlus/b)), tool that allows you to copy your Bitwarden/Vaultwarden password directly from your terminal.*
</center>

### Why?

It works for me. You run it in a shell session. The first time, it will prompt you for the master password, but consecutive times that you run `b` within the session, the vault will already be unlocked. I use it on a dwm st scratchpad, by the way.

### Demo

![](b.gif)

### Dependencies

- `bw`
- `xclip`
- `jq`
- `fzf`

### Installation

Move the `b` file to `~/.local/bin`.

```shell
mv b /usr/local/bin
```

Create the alias to run the program from the current context:
```shell
alias b=". ~/.local/bin/bkekw"
```

### Usage
Search for a password :
```shell
# ex, search github password
b github
```

