# Requirements
```sh
https://github.com/imthaghost/goclone
https://www.goclone.io/
```
### Homebrew installation 
```sh
$ sudo apt update
$ sudo apt install build-essential curl git

$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

$ echo 'eval "$(/home/user/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.profile
$ eval "$(/home/user/linuxbrew/.linuxbrew/bin/brew shellenv)"

$ brew doctor 
# Your system is ready to brew
```
### Goclone installation 
```sh
$ brew tap imthaghost/goclone 
$ brew install goclone 

# goclone help command 
$ goclone --help, -h

# run command
# Use current directory
$ goclone https://www.example.com/login.php
```
