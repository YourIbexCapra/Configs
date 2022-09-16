# ZSH Config Install

## ZSH

```shell
sudo apt install zsh -y
chsh -s $(which zsh)
sudo reboot
```

## Oh-My-Zsh

```shell
cd ~/
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Configs

```shell
cp .zshrc ~/
cp ./YourIbexCapra.zsh-theme ~/.oh-my-zsh/themes
```

## Plugins

```shell
cd ~/.oh-my-zsh/plugins
git clone https://github.com/zsh-users/zsh-autosuggestions.git
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
```
