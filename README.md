# bigbank

## NodeJs Install ##
```
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
  nvm install node
```
## Firebase Install ##
```
  npm install -g firebase-tools
  npm install -g firebase-functions
  npm install -g firebase-admin  
```
## Bigbank on Firebase ##
```
  git config --global user.email "user@mail.com"
  git config --global user.name "user"
  git clone https://github.com/cmadera/bigbank.git
  cd bigbank/

  firebase login
  firebase init
  code .

  git add .
  git commit -m "new version"
  git push


  firebase deploy
```

## Ubuntu Alias ##
vi .bashrc
```
alias get='sudo apt-get install -y'
alias df='df -h'
alias ls='ls -la'
alias upgrade='sudo apt-get update -y && sudo apt-get full-upgrade -y && sudo apt-get autoremove -y'
alias cdwww='cd /var/www/html'
alias myip='curl ifconfig.me'
alias version='lsb_release -a'

```
get curl git net-tools build-essential tmux cockpit

## CentOS Alias ##
vi .bashrc
```
alias get='sudo yum install -y'
alias df='df -h'
alias ls='ls -la'
alias upgrade='sudo yum update -y'
alias cdwww='cd /var/www/html'
alias myip='curl ifconfig.me'
alias version='hostnamectl'

```
get curl

