# homebrew apps
tap 'homebrew/bundle'
tap 'homebrew/core'
tap 'go-delve/delve'
tap 'kryptco/tap'
# -------------------------
brew 'bash-completion'
brew 'git'

brew 'hugo'
brew 'mackup'
brew 'n'
brew 'jq'
brew 'gpm'
brew 'shellcheck'
brew 'ssh-copy-id'
brew 'tree'
brew 'vault'
brew 'wget', args: ['with-iri']
brew 'grep' #, args: ['with-default-names']
brew 'wrk'
brew 'upx'
brew 'telnet'

# ZSH Stuff
brew 'zsh'
brew 'zsh-completions'
brew 'zsh-syntax-highlighting'
# https://github.com/bhilburn/powerlevel9k
tap 'sambadevi/powerlevel9k'
brew 'powerlevel9k'

# Install GNU core utilities (those that come with macOS are outdated)
brew 'coreutils'

# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
brew 'findutils'

# Other GNU utils
brew 'gnu-sed'#, args: ['with-default-names']
brew 'gnu-tar'#, args: ['with-default-names']
brew 'gnu-which'#, args: ['with-default-names']

# Go Stuff
brew 'go'
brew 'kubectl'
brew 'kubernetes-helm'

# Python 
brew 'python'
brew 'pyenv'
brew 'pyenv-virtualenv'
# optional, but recommended for pyenv
# NOTE: openssl is recommened no matter what
brew 'openssl'
brew 'readline'
brew 'sqlite3'
brew 'xz'
brew 'zlib'

# React
brew 'yarn', args: ['without-node']
# Watchman is a tool by Facebook for watching changes in the filesystem.
brew 'watchman'

# secure ssh
brew 'kryptco/tap/kr'

# dependencies
brew 'gdbm'
brew 'pcre'
brew 'libidn'

#
# install casks
# 

tap 'homebrew/cask'
cask_args appdir: '/Applications'
# -------------------------
cask 'atom'
cask 'visual-studio-code'
cask 'github'
cask 'google-chrome'
cask 'google-cloud-sdk'
cask 'kitematic'
cask 'iterm2'
cask 'hyper'
cask 'keepingyouawake'
cask 'slack'
cask 'spectacle'
cask 'spotify'

# --- Other ---
# cask 'cheatsheet'
# cask 'filezilla'
# cask 'handbrake'
# cask 'keybase'
# cask 'telegram'
# cask 'sketch'
# cask 'ngrok'

# API tool
cask 'insomnia'

# minikube uses virtualbox so it must be first
cask 'virtualbox' 
cask 'minikube'

# SQL tool
cask 'popsql'

# https://github.com/buo/homebrew-cask-upgrade
# brew-cask-upgrade is a command-line tool for upgrading every 
# outdated app installed by Homebrew Cask.
tap 'buo/cask-upgrade'

# install fonts
tap 'homebrew/cask-fonts'
# --------------------------
cask 'font-hack'
cask 'font-hasklig'
cask 'font-monoid'
cask 'font-source-code-pro'
cask 'font-iosevka'
cask 'font-input'

# install app store apps
# https://github.com/mas-cli/mas
# -------------------------
brew 'mas'
# -------------------------
mas 'Microsoft Remote Desktop', id: 1295203466
# mas 'Xcode', id: 497799835
mas 'Slack', id: 803453959
mas 'Evernote', id: 406056744
mas 'Todoist', id: 585829637


# --- native apps 2019 ---
# mas 'GarageBand', id: 682658836
# mas 'iMovie', id: 408981434
# mas 'Pages', id: 409201541
# mas 'Keynote', id: 409183694
# mas 'Numbers', id: 409203825

# --- Other ---
# mas 'Clear', id: 504544917
# mas 'Skitch', id: 425955336
# mas 'Bitcoin Expert', id: 1237809495
# mas 'Twitter', id: 409789998
# mas 'iPhoto', id: 408981381
# mas 'TurboTax 2015', id: 1061844571
# mas 'LastPass', id: 926036361
# mas 'Aperture', id: 408981426
# mas "Blackmagic Disk Speed Test", id: 425264550
# mas "CARROT Weather", id: 993487541
# mas "CCMenu", id: 603117688
# mas "DrCleaner", id: 921458519
# mas "Frame.io", id: 992958444
# mas "Magnet", id: 441258766
# mas "QuickBooks", id: 640830064
# mas "WiFi Explorer", id: 494803304
# mas "WiFi Signal", id: 525912054


# ***  Examples ***
# tap 'telemachus/brew', 'https://telemachus@bitbucket.org/telemachus/brew.git'
# brew 'imagemagick'
# brew 'mysql', restart_service: true, conflicts_with: ['homebrew/versions/mysql56']
# brew 'emacs', args: ['with-cocoa', 'with-gnutls']
# cask 'google-chrome'
# cask 'java' unless system '/usr/libexec/java_home --failfast'
# cask 'firefox', args: { appdir: '~/my-apps/Applications' }


# Homebrew Services
# Integrates Homebrew formulae with macOS' launchctl manager.
# -------------------------

# Start the MySQL service at login with:
# brew services start mysql

# Start the Dnsmasq service at boot with:
# sudo brew services start dnsmasq

# Start all available services with:
# brew services start --all