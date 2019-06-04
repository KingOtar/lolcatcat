# LolCatCat
This is a collection of bash scripts to alias and manage your commands to pipe their outputs into lolcat. For the lulz.

## Install
Clone this repo and and source the lolcat script.
```
git clone https://github.com/KingOtar/lolcatcat.git ~/lolcatcat
echo "source ~/lolcatcat/lolcatcat" >> .bash_profile
```

## Usage
The script reads out of the  file by default for the list of commands to pipe to lolcat and adds alias scripts to `~/.lolcatcat/aliases`

You can execute the `addlolcat` and `rmlolcat` commands to add or remove commands from the list or edit `~/.lolcatcat/commands` manually.

## Requirements
`lolcat` must be installed and in the $PATH variable.

## Warning
Be careful on which commands are added to this script. They are potentially breaking. Test before usage.

