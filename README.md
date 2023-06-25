# test

# Development

IDE:

    pycharm
    intellibot
    IdeaVIM
    
python library:
 
    pip
    setuptools
    wheel
    virtualenv
    virtualenvwrapper

# Install

dependency:

    sudo apt-get install sshpass
    sudo apt-get install pandoc
    sudo apt-get install helix-cli
    sudo apt-get install nfs-common

pre-install for firefox:

    geckodriver 0.19.0
    Firefox 55.0 (and greater)
    Selenium 3.5 (and greater)
    
pre-install for chrome:

    chromedriver 2.33
    Chrome v60-62
    Selenium 3.5

install from source code:

    $ cd test
    $ pip install --user -r requirements.txt
    $ sudo python setup.py install --user --record install_1.3.1.log

upgrade from source code:

    $ cd test
    $ git pull
    $ cat install_1.3.0.log | xargs sudo rm -rf
    $ pip install --user -r requirements.txt
    $ sudo python setup.py install --force --user --record install_1.3.1.log

## Deploy server(controller)

dependency:

    sudo apt-get install unzip sshpass

## Release server

dependency:

    sudo apt-get install sshpass

# Issue

1. intellibot can not refactor robot file when keywords renamed in python code.
