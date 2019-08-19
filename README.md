# 1.1.1 Computer Setup

## Setup your development environment

Some of the following tools require the use of the terminal (Terminal.app). This can be quite overwhelming if you've never used it before, but don't worry, you'll soon grow comfortable with it.

The easiest way to open an application is to search for it via Spotlight. To open Spotlight using the default keyboard shortcut, press the command key (⌘) and tap the space bar. Once Spotlight is up, type the first few letters of the app you are looking for, and once it appears, select it, and press return to launch it.

## Homebrew and Xcode

This guide assumes you are on a Mac and will be using homebrew.

Install Xcode package:

```
$ xcode-select --install
```

Click through all confirmation commands.

Install homebrew:

```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew doctor
```

## Python Versions with Homebrew

You can manage python versions with Homebrew. 

Install Python 3:

```
$ brew update
$ brew install python3
```

Verify Python 3:

```
$ python3 --version
Python 3.6.X
```

Verify Python 2.7 still works:

```
$ python
Python 2.7.X (default, Dec 18 2016, 07:03:39)
[GCC 4.2.1 Compatible Apple LLVM 8.0.0 (clang-800.0.42.1)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
```

Use `exit()` or `Ctrl-D` to exit the interactive shell.

## Pipenv

Pipenv is designed to combine pip and virtualenv into one program. It has become the official Python-recommended resource for managing package dependencies.

Install Pipenv for Python 3:

```
$ pip3 install -U pipenv
$ echo -e 'eval "$(pipenv --completion)"' >> ~/.profile
$ source ~/.profile
```

Install Pipenv for Python 2 **(optional)**:

```
$ pip install -U pipenv
```

## Apps

* [Install Google Chrome for Mac](https://www.google.com/chrome/)
* [Install Atom](https://atom.io/)
* [Install Slack](https://slack.com/downloads/mac)
* [Create a GitHub Account](https://github.com/)
* [Install PyCharm](https://www.jetbrains.com/pycharm/)

## Create an SSH key

You'll need an SSH key when using Github. SSH keys are a way to identify trusted computers, without involving passwords. Walk through the steps in the following tutorial to create your SSH key and add it to your Github account. Read the instructions completely, don't skim or skip. *Make sure to read the instructions carefully, the tutorial tells you everything you need to do.* [https://help.github.com/articles/generating-ssh-keys](https://help.github.com/articles/generating-ssh-keys)
