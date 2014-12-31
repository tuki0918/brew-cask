# Setup Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Usage
```
bash ./Caskfile
```

----

# Install App Search
	+ brew install caskroom/cask/brew-cask
```
brew cask search [search app name]
```

# Install App
```
cask install <app_name> || true
```

# Uninstall App
```
brew cask uninstall <app_name>
```

# Etc
```
brew update && brew upgrade brew-cask && brew cleanup
```