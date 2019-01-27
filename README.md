# Multi ssh for iterm2

AppleScript for launching custom arrangement of the windows for iTerm. 

You can setup different profiles  for each environment that you need.

:bangbang: Script presume that you have iTerm installed under /Applications with name iTerm.app


## Instalation
copy  itermmssh.scpt to ~/Library/Application Support/iTerm2/Scripts 

```cp itermmssh.scpt ~/Library/Application\ Support/iTerm2/Scripts```

copy terminal.ini to your home folder(sample imput is added)

```cp terminal.ini ~/```

## edit config file - terminal.ini

### setup common variables
under section [common] are for now only two settings
columns=<number> . --> represents number of columns, rows are calculated depending on number of items in profile
delay=< seconds > --> delay of the execution of the next delay
### setup sessions
in each profile you can set up
name and command

Example: machine1=ssh root@mybestmachine

