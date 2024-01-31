# Funk - Custom function maker / manager

Note: functions are called from from .bashrc and are in the .funk/functions file - which also includes the description (if there is one)

## Usage: 

`funk` - list functions created with this tool (or show instructions if none) - in the format of name command description (if there is one)

`funk add name 'command' 'description' confirm?`

eg. add duh 'du -h' 'human disk usage' y - will bring up duh - human disk usage - are you sure? but without the y won't ask if you are sure, but just run it - in either case it will source $HOME/.funk/functions so it is available

`funk del name` - delete function

`funk edit` - call default editor to edit .funk/functions

`funk help` - show instructions

## To Do

if not there add to .bashrc (or .zshrc) -

`source "$HOME/.funk/functions"`

`chmod +x funk` & move to an accessible path

Stop it allowing duplicate functions with the same name
