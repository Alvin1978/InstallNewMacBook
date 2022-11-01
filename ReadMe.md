
### Downloads 
* [spotify](https://www.spotify.com/us/download/mac/)
* [VS Code](https://code.visualstudio.com/Download)
* [Powershell for Mac](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-macos?view=powershell-7.2)
* [Firefox](https://www.mozilla.org/nb-NO/firefox/mac/)
* [Microsoft Edge](https://www.microsoft.com/en-us/edge?r=1#evergreen)
* [chrome](https://www.google.com/chrome/)
* [Bitwarden](https://bitwarden.com/download/)
* [Rectangle](https://rectangleapp.com/)

### Other Downloads
* [Citrix Receiver for Mac](https://www.citrix.com/downloads/citrix-receiver/mac/)
* [Download Microsoft Company Portal for Mac](https://go.microsoft.com/fwlink/?linkid=853070)
* [1password](https://1password.com/downloads/)
* [evernote](https://evernote.com/download)
* [docker](https://store.docker.com/editions/community/docker-ce-desktop-mac)
* [iterm2](https://www.iterm2.com/downloads.html)
* [istats](https://bjango.com/mac/istatmenus/)
* [mysql workbench](https://dev.mysql.com/downloads/workbench/)
* [Slack](https://slack.com/beta/mac)
* [ShiftIt](https://github.com/fikovnik/ShiftIt/releases)

## Install HomneBrew
### install [homebrew] (https://docs.brew.sh/Installation)
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
####
To Update Brew
```
brew update
```
## Install xCode (Used for Git & PWSH
```
xcode-select --install
```
## Install GIT
[Install and set up Git](https://learn.microsoft.com/en-us/devops/develop/git/install-and-set-up-git)
### it's recommended that you install Git through Homebrew 
```
brew install git
```
### To update the Git install, use Homebrew's upgrade option:
```
brew upgrade git
```
### Configure Git
```bash
# git configuration setup
# git config --global push.default simple
# git config --global core.editor "vim"

# Set name and email in gitconfig
# git config --global user.name "Øyvind Pettersen"
# git config --global user.email johndoe@example.com
# git config --global push.default current

# Generate SSH keys (provide a good passphrase when asked)
ssh-keygen -t rsa -C "johndoe@example.com"

cd ~
```
