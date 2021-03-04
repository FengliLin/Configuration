# Configuration
MacBookPro Configurations

## Homebrew
For China network
`/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"`

## iTerm2
Download from [https://www.iterm2.com/index.html]

## zsh
`brew install zsh zsh-completions`

## oh-my-zsh
`sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

## Plugins
### autojump
1. `brew install autojump`
2. `plugins=(autojump)`

### zsh-autosuggestions
1. `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
2. `plugins=(zsh-autosuggestions)`
3. add `bindkey ',' autosuggest-accept` to ~/.zshrc

### zsh-syntax-highlighting
1. `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
2. `plugins=( [plugins...] zsh-syntax-highlighting)`  MUST BE THE LAST ONE
