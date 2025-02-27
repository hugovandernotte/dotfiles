# Install packages

- brew install wezterm
- brew install fish
- brew install starship
- brew install fzf
- brew install fd
- brew install bat
- brew install zellij
  
font: https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/IntelOneMono.zip


# Update config files

### ~/.config/fish/config.fish

starship init fish | source
fzf --fish | source

# Remove fish greeting: 
set -U fish_greeting ""

# Themes

- wezterm: https://github.com/neapsix/wezterm
