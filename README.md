# Multi ssh for iterm2

Does not install anything or give machine any special previleges.

## installation
copy  itemmssh.scpt to ~/Library/Application Support/iTerm2/Scripts 
```cp itemmssh.scpt ~/Library/Application\ Support/iTerm2/Scripts```

copy terminal.ini to your home folder(sample imput is added)

```cp terminal.ini ~/```

## edit config file - terminal.ini

### setup common variables
under section [common] are for now only two settings
columns=<number> . --> represents number of columns, rows are calculated depending on number of items in profile
delay=< seconds > --> delay of the execution of the nex delay
### setup sessions
in each profile you can set up
name and command

Example: machine1=ssh root@mybestmachine

