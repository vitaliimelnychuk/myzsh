# myzsh

My ZSH setup, aliases, and dotfiles.

# Projects configurations

As far a there are some personal and coroporative projects that I am working on, they all stored in one file called `projects.zsh`.

# Secrets management

To avoid any sensative information under Git it's stored in the `secrets.zsh`


## Tools installation

- Xcode

```bash
xcode-select —-install
```

- [Brew](https://brew.sh/)

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

```bash
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zshrc
    eval "$(/opt/homebrew/bin/brew shellenv)"
```


Install all applications
```bash
brew install zsh iterm2 wget
```

- [Oh my ZSH](https://github.com/ohmyzsh/ohmyzsh)

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Docker plugin
```bash
git clone https://github.com/zsh-users/zsh-docker.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-docker
```

Update your changes by running the command source `~/.zshrc`

- [NVM](https://github.com/nvm-sh/nvm)

```bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

- [GnuPG](https://www.gnupg.org/download/)

    - Install from website
    - Follow GitHub/Gitlab documentation to add new keys to sign
