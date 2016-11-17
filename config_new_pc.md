**Neuen Mac aufsetzen**
---------------------------

Firefox installieren

iterm2 installieren:
[*https://www.iterm2.com/*](https://www.iterm2.com/)

homebrew installieren: [*http://brew.sh/*](http://brew.sh/)

brew install rbenv ruby-build

xcode-select --install

brew install macvim

brew install git


**git & gitconfig**

git config --global andre.jaehrling "André Jährling"

git config --global user.email andre.jaehrling@blau.de

git config --global alias.co checkout

git config --global alias.st status

https://github.com/so-fancy/diff-so-fancy


**zsh**

brew install zsh

gem install homesick

homesick clone drdent/zsh\_config

homesick symlink zsh\_config

iterm profil command /usr/local/bin/zsh

cd zsh_config && sh relink_dotfiles.sh


**mac vim**

homesick clone drdent/vim\_config

homesick symlink vim\_config

cd vimconfig && git submodule update --init --recursive

brew install ctags

brew install autojump


**Tools**

Office for Mac

Adium / Slack

DBVisualizer

Dropbox

Virtual Box

Photoshop

MenuMeters
