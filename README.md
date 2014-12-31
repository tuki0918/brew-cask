# Setup Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Usage
```
bash ./Caskfile
```

# Install App
```
cask install <app_name> || true
```

# Uninstall App
```
brew cask uninstall <app_name>
```

# Install App Search
```
brew cask search [search app name]
```

# Etc
```
brew update && brew upgrade brew-cask && brew cleanup
```