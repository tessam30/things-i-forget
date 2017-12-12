# Python startup


## Installation
All commands are at terminal unless otherwise specified, and current as of December 2017.
### Python + helpers
* Download and install [NodeJS](https://nodejs.org/en/)
* ```npm install -g http-server```
* Install [Homebrew](https://brew.sh/) ```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```
* Update Homebrew ```brew update```
 * **Double check before installing** Believe this solves permission issues that Homebrew has with admin (gets around sudo-ing) -- but I might be misremembering, and this might not be necessary.
 ```echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile```
 * Install [Python](https://www.python.org/) ```brew install python``` or ```brew install python3```
 * Update pip: ```install --upgrade distribute```
 ```install --upgrade pip setuptools```
 ```python3 -m pip install --upgrade pip```

### Useful packages
* Install [Jupyter](http://jupyter.org/install.html) ```python3 -m pip install jupyter```
* ```pip2 install pandas```
* ```brew install numpy```
* ```brew install scipy```
* ```pip2 install scikit-learn```
* ```pip2 install seaborn```
* ```pip2 install Flask```

## Version and other checks
* Node: ```node -v```
* NPM: ```npm -v```
* Homebrew: ```brew doctor```
* python: ```which python``` (where installed); ```python --v``` (version)
* python packages: ```pip2 list```


## Python basics
* Launch: ```python3``` or ```python```
* Quit: ```quit()``` or ```Ctrl-D``` from within Python; ```ctrl-C``` from Jupyter notebook
* Jupyter notebook: ```jupyter notebook``` (lauches in current working directory)
