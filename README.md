# Configuration
MacBookPro Configurations

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

### zsh-syntax-highlighting
1. `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
2. `plugins=( [plugins...] zsh-syntax-highlighting)`  MUST BE THE LAST ONE
