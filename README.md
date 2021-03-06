# Gedi
A python code completion plugin for gedit. Built with the Jedi auto completion library by David Halter (https://github.com/davidhalter/jedi).

![Example](/screenshots/completion-1.png)

## Current Features:
- Autocompletion

## Planned Features:
- Find Definition
- Some refactoring tools

## Using
- Firstly, you need to install jedi. You can install it (search for python3-jedi) from your distro's package manager (sometimes neccessary) or you can install it with pip:
```
pip install jedi
```
- For Ubuntu distro, install python3-jedi using command :
```
sudo apt-get install python3-jedi
```
- Download the project.
- Extract the files to /home/YOUR_USER_NAME/.local/share/gedit/plugins
- If the directory .local/share/gedit/plugins/ is not present, create it.
- Open gedit, go to Preferences > Plugins > Gedi to activate it.
- Restart gedit.

Instead of downloading you can just clone the project to your plugin path:
```
$ mkdir -p ~/.local/share/gedit/plugins
$ cd ~/.local/share/gedit/plugins
$ git clone https://github.com/isamert/gedi.git
```
For updating:
```
$ cd ~/.local/share/gedit/plugins/gedi
$ git pull
```
