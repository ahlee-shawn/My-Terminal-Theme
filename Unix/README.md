## Install My Terminal Theme on Unix (Including Ubuntu/RedHat)

1. Install zsh
For Ubuntu:
```
sudo apt install zsh
```
For RedHat:
```
sudo yum install zsh -y
```

2. Change shell to zsh
```
chsh -s $(which zsh)
```

3. Install Oh My Zsh
```
sh -c “$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)”
```

4. Chech zsh version
```
echo $ZSH_VERSION
```

5. Install Powerlevel10k (For zsh version >= 5.1)
```
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

6. Edit .zshrc in home directory
```
ZSH_THEME="powerlevel10k/powerlevel10k" or "agnoster"
```

7. Auto-Suggestion
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

8. Syntax Highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

9. Edit .zshrc in home directory
```
plugins=(zsh-autosuggestions zsh-syntax-highlighting)
```