
### Downloads 
* [spotify](https://www.spotify.com/us/download/mac/)
* [VS Code](https://code.visualstudio.com/Download)
* [Firefox](https://www.mozilla.org/nb-NO/firefox/mac/)
* [Microsoft Edge](https://www.microsoft.com/en-us/edge?r=1#evergreen)
* [chrome](https://www.google.com/chrome/)

### Other Downloads
* [1password](https://1password.com/downloads/)
* [evernote](https://evernote.com/download)
* [docker](https://store.docker.com/editions/community/docker-ce-desktop-mac)
* [iterm2](https://www.iterm2.com/downloads.html)
* [istats](https://bjango.com/mac/istatmenus/)
* [mysql workbench](https://dev.mysql.com/downloads/workbench/)
* [Slack](https://slack.com/beta/mac)
* [ShiftIt](https://github.com/fikovnik/ShiftIt/releases)

### Install HomneBrew
# install [homebrew] (https://docs.brew.sh/Installation)
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### Development
```bash
# git configuration setup
# git config --global push.default simple
# git config --global core.editor "vim"

# Set name and email in gitconfig
# git config --global user.name "Justin Soliz"
# git config --global user.email johndoe@example.com
# git config --global push.default current

# Generate SSH keys (provide a good passphrase when asked)
ssh-keygen -t rsa -C "johndoe@example.com"




# install dot files
# https://github.com/justinsoliz/dotfiles

## Node
# nvm/node.js
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash

# install node versions
nvm i 8
nvm i 10

# install yarn (without node)
* [How to Install Yarn on MacOS](https://tecadmin.net/install-yarn-macos/)
brew install yarn --without-node


cd ~

## install other random things
# Tree - Display directories as trees (with optional color/HTML output)
brew install tree
```
