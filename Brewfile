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
brew 'openssl'
brew 'shellcheck'
brew 'ssh-copy-id'
brew 'lastpass-cli', args: ['with-pinentry', 'with-doc']
brew 'tree'
brew 'vault'
brew 'wget', args: ['with-iri']
brew 'grep' #, args: ['with-default-names']
brew 'zsh'
brew 'zsh-completions'
brew 'wrk'
brew 'upx'
brew 'telnet'

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

# Python 3
brew 'python'

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

# install casks
# tap 'caskroom/cask'
cask_args appdir: '/Applications'
# -------------------------
cask 'atom'
cask 'visual-studio-code'
# cask 'cheatsheet'
# cask 'filezilla'
cask 'github'
cask 'google-chrome'
cask 'google-cloud-sdk'
cask 'kitematic'
# cask 'handbrake'
cask 'iterm2'
cask 'keepingyouawake'
cask 'slack'
cask 'spectacle'
cask 'spotify'
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
brew 'mas'
# -------------------------
# mas 'Clear', id: 504544917
# mas 'Skitch', id: 425955336
mas 'Microsoft Remote Desktop', id: 1295203466
mas 'Xcode', id: 497799835
mas 'Slack', id: 803453959
mas 'Evernote', id: 406056744
mas 'Todoist', id: 585829637



# ---- native apps 2019
#682658836 GarageBand (10.3.2)
#408981434 iMovie (10.1.10)
#409201541 Pages (7.3)
#409183694 Keynote (8.3)
#409203825 Numbers (5.3)


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
# 
# Azure Pipelines
# 
# Requirements
# Homebrew is used for installing the services.
# 
# This does not work with Linuxbrew (so don't file Linux issues, please).
# 
# Install
# brew services is automatically installed when run.
# 
# Usage
# ==Start==

# Start the MySQL service at login with:
# brew services start mysql

# Start the Dnsmasq service at boot with:
# sudo brew services start dnsmasq

# Start all available services with:
# brew services start --all

# ==Run==
# Run the MySQL service but don't start it at login (nor boot) with:
# brew services run mysql
# 
# Stop
# Stop the MySQL service with:
# brew services stop mysql
# 
# Restart
# Restart the MySQL service with:
# brew services restart mysql
#
# List
# List all services managed by brew services with:
# brew services list
#
# Cleanup
# Remove all unused services with:
# brew services cleanup
