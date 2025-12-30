# starship_config
Personal config files for Starship rs
The goal is just to have a portable config that I can use for any machine. This is for zsh

# Setup
## 1. Make sure a Nerd Font is installed and in use
- Nerd Font: https://www.nerdfonts.com/
- In iterm2, that is Settings->Profile->Text->Font
- Use FiraCode Nerd Mono if nothing else
## 2. Install starship
[Install starship rs](https://starship.rs/installing/)
Probably just
```bash
brew install starship
```
## 3. Alter the config location for starship
This is a slight alteration that allows us to use a better repository structure
```bash
echo 'export STARSHIP_CONFIG="$HOME/.config/starship/starship.toml"' >> $HOME/.zshrc
```
## 4. Clone this repository
```bash
git clone git@github.com:jcooper036/starship_config.git ~/.config/starship
```

