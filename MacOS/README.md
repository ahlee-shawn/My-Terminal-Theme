## Install My Terminal Theme on MacOS

1. Install CLI Tools for Xcode
```
sudo xcode-select --install
```

2. Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3. Install iTerm2
```
brew install --cask iterm2
```

4. Install zsh
```
brew install zsh
```

5. Install Oh My Zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

6. Install Powerlevel10k
```
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

7. Edit .zshrc in home directory
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

8. Auto-Suggestion
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

9. Edit .zshrc in home directory
```
plugins=(zsh-autosuggestions)
```

10. Syntax Highlighting
```
brew install zsh-syntax-highlighting
```
11. Add this line to .zshrc in home directory
```
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

12. Visual Studio Code Terminal Config
```
"terminal.integrated.fontFamily": "MesloLGS NF"
```

13. Change Terminal Background Color in iTerm
```
R: 48
G: 56
B: 65
```