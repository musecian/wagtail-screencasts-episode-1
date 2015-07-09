# Description
It contains all the files used in the making of the screencasts: "how to setup wagtail on windows".

# Contents
1. A vagrant file
  Create a folder called wagtail-vm in drive C and copy this file inside.

# Commands mentioned in the screencast
- Navigating to the wagtail-vm folder in drive C using the git bash terminal.
  `cd C:/wagtail-vm`
- Staring vagrant.
  `vagrant up`
- Logging into the vagrant VM.
  `vagrant up`
- Creating the wagtail-tutorial folder in the home directory of the vagrant box.
  `mkdir wagtail-tutorial`
- Navigating to the wagtail-tutorial folder in the home directory of the vagrant box.
  `cd wagtail-tutorial`
- Creating a virtual environment.
  `mkvirtualenv wagtail-tutorial`
- Installing wagtail using pip.
  `pip install wagtail`
- Creating a wagtail project.
  `start wagtail hellowagtail`
- Running a migration.
  `./manage.py migrate`
- Starting the django server.
  `./manage.py runserver 0.0.0.0:8000`

# Links mentioned in the video:
- The vagrant download page: https://www.vagrantup.com/downloads.html
- Git for windows download: https://git-scm.com/download/win
- Virtualenvwrapper: https://virtualenvwrapper.readthedocs.org/en/latest/index.html

# Extras:
- To use the Git bash terminal as I am using it in the tutorial. You can check out [this](https://scotch.io/tutorials/get-a-functional-and-sleek-console-in-windows) tutorial that shows how to setup ConEmu with gitbash.
