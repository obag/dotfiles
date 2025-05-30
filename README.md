# obag - dotfiles
My config files for linux programs eg. fish, vim, kitty.

## Installation

### 1. Install Dependencies

**Ubuntu Based**
```sh
sudo apt install git fish stow
```

**Fedora Based**
```sh
sudo dnf install git fish stow
```

**Arch Based**
```sh
sudo pacman -S git fish stow
```

I use [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) to theme my shell. To install:
```sh
curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish
```

I use the theme bobthefish. To install:
```sh
omf install bobthefish
```

### 2. Install dotfiles
clone the repository to your home directory:
```
cd
git clone https://github.com/obag/dotfiles
```

Stow the files:
```sh
stow . --adopt
git restore .
```


