# bashrc
terminal commands I have found useful
alias v="cd ../"
alias vv="cd ../../"
alias vvv="cd ../../../"
alias f="ls -al"
alias t="touch"
alias md="mkdir"
alias rd="rmdir"
alias s="subl3"
alias fire="firefox"
alias c="clear"
alias cp="cp -i"                          # confirm before overwriting something
alias df='df -h'                          # human-readable sizes
alias free='free -m'                      # show sizes in MB
alias tis="touch index.html styles.css"
alias u="pwd | xclip -sel clip & pwd"
alias openalias="s ~/.bashrc" #open aliases in my current text editor, sublime
alias sf="screenfetch" #program for seeing basic info on screen. 
alias fixit='sudo rm -f /var/lib/pacman/db.lck && sudo pacman-mirrors -g && sudo pacman -Syyuu  && sudo pacman -Suu'
alias ff="sudo pacman -Syyu" #update my packages
The last 2 are manjaroLinux specific. 
