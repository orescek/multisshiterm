# Multi ssh for iterm2

AppleScript for launching custom arrangement of the windows for iTerm. 

You can setup different profiles  for each environment that you need.

:bangbang: Script presume that you have iTerm installed under /Applications with name iTerm.app


## Instalation
Copy  itermmssh.scpt to:  ~/Library/Application Support/iTerm2/Scripts 

```cp itermmssh.scpt ~/Library/Application\ Support/iTerm2/Scripts```

Copy terminal.ini to your home folder(in file is sample input):

```cp terminal.ini ~/```

## Edit config file - terminal.ini

### Setup common variables
under section [common] are for now only two settings
columns=<number> . --> represents number of columns, rows are calculated depending on number of items in profile
delay=< seconds > --> delay of the execution of the next delay
### setup profiles
Each profile should start with [ and end with ] 

Example: ```[Some profile name]```

After defining profile name you can setup your profile with name of the window and what should it do

Example: ```machine1=ssh root@mybestmachine```

You can override common settings for each profile.
