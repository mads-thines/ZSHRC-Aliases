# ZSHRC-Aliases

### What's it for?
Using aliases decreases your workload by decreasing the amount of typing, which will increases your overall performance.
Great, right?

### Dependencies
- Bash Terminal
- Zsh
- Oh My Zsh.

### Setup
##### Run the following command in your root folder where the .zshrc file is located.
```bash
test -f ~/.oh-my-zsh/custom/aliases || mkdir ~/.oh-my-zsh/custom/aliases
cd ~/.oh-my-zsh/custom/aliases && git clone https://github.com/mthines/zshrc-aliases.git

echo "
# ZSHRC Aliases
source ~/.oh-my-zsh/custom/aliases/zshrc-aliases/.zshrc-aliases
" >> ~/.zshrc
```
##### Or add the following lines in the bottom of your .zsh file
```bash
echo "
# ZSHRC Aliases
source ~/.oh-my-zsh/custom/aliases/zshrc-aliases/.zshrc-aliases
" >> ~/.zshrc
```
### And then run or reopen your terminal and enjoy the aliases for a faster workflow.
```bash
source ~/.zshrc
```

### Recommended other plugins

https://safjan.com/top-popular-zsh-plugins-on-github/

- https://github.com/wting/autojump
- https://github.com/zsh-users/zsh-autosuggestions
- https://github.com/bobthecow/git-flow-completion
- zsh-syntax-highlighting

