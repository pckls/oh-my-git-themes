# oh-my-git-themes

This is just a place to store my own themes for [oh-my-git](https://github.com/arialdomartini/oh-my-git).

If you wanted to try this out just install [antigen](https://github.com/zsh-users/antigen):

```
cd ~ && git clone https://github.com/zsh-users/antigen.git .antigen 
```

And then add the following lines to your `.zshrc`:

```
source "$HOME/.antigen/antigen.zsh"
antigen-use oh-my-zsh
antigen-bundle arialdomartini/oh-my-git
antigen theme pckls/oh-my-git-themes pckls-pathinline
antigen-apply
```

Enjoy!

