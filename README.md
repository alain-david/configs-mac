# Mac configs

# System Preferences

- Login Apple ID

### Networks

- Activar Firewall

### General

- Actualizar el sistema
- Storage in Icloud

### Appearance

- Theme Dark
- Show scroll bars: When scrolling.

### Control Center

- Menubar (Remover iconos y mostrar % de batería).
- Automatically hide and show menu bar: always.

### Siri & Spotlight

- Spotlight (Quitar fonts, images, files etc).

### Desktop & Dock

- Ajustar Dock
- Automatically hide and show the dock: true
- Show indicators for open apps: true
- Show suggested apps: false
- Hot Corners: empty

### Display

- Night Shift: 7pm to 7 am.

### Wallpapers

### Internet Accounts

- Add Google accounts.

### Mouse

- Natural scrolling.

### Trackpad

- Enable tap to click with one finger.
- Scroll & Zoom: Uncheckj all apart from Zoom in and out.

### Apps

- Finder Settings

# Instalar Xcode

Desde la AppStore y después:

```bash
xcode-select --install
```

# Instalar Homebrew

Desde la web o usando:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Agregar Homebrew al path.

```bash
echo 'PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile
```

Comprobar que todo este bien:

```bash
brew doctor
```

Instalar Tools:

```bash
brew install \
    neofetch \
    neovim \
    git
```

Configurar Git:

```bash
git config --global user.name "Alain Puga"
git config --global user.email "kiritothepunisher@gmail.com"
git config --global credential.helper osxkeychain
git config --global init.defaultBranch main
```

# Instalar Oh My Zsh

Desde la web o usando:

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Instalar Plugin Autosuggestions:

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

Clonar repo:

```bash
git clone https://alain-david/mac-configs
```

Instalar Apps:

```bash
brew install --cask \
    betterzip \
    brave-browser \
    visual-studio-code
```

# Apps

- CleanMyMac
- Unarchiver https://theunarchiver.com
- Whatsapp
- Discord

## FrontEnd

### Angular

Instalar NodeJS:

```bash
brew install node
```

Instalar Yarn: https://yarnpkg.com/getting-started/install

Instalar Angular CLI:

```
yarn install -g @angular/cli
```

## Backend

- Postman
- Docker
- Go

### Go

```bash
brew install go
```

## Mobile

- Flutter
- IOS Environment
- Android Environment

### IOS Environment

Instalar Ruby Env:

```bash
brew install rbenv ruby-build rbenv-default-gems rbenv-gemset
```

Instalar Cocoapods:

```bash
brew install cocoapods
```

## BD

- MongoDB Compass
- RedisInsight
- Table Plus

## Imagenes

- GIMP
