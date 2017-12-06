# bashrc
terminal commands I have found useful
1. alias v="cd ../"
2. alias vv="cd ../../"
3. alias vvv="cd ../../../"
4. alias f="ls -al"
5. alias t="touch"
6. alias md="mkdir"
7. alias rd="rmdir"
8. alias s="subl3"
9. alias fire="firefox"
10. alias c="clear"
11. alias cp="cp -i"                          # confirm before overwriting something
12. alias df='df -h'                          # human-readable sizes
13. alias free='free -m'                      # show sizes in MB
14. alias tis="touch index.html styles.css"
15. alias u="pwd | xclip -sel clip & pwd"
16. alias openalias="s ~/.bashrc" #open aliases in my current text editor, sublime
17. alias sf="screenfetch" #program for seeing basic info on screen. 
18. alias fixit='sudo rm -f /var/lib/pacman/db.lck && sudo pacman-mirrors -g && sudo pacman -Syyuu  && sudo pacman -Suu'
19. alias ff="sudo pacman -Syyu" #update my packages...The last 2 are manjaroLinux specific. 
20. alias howbig="du -sh" #usage as-->howbig fileOrFoldername -- -h human readable, -s summary


.# speaking of aliases, check out this bit of command line voodoo...
.# history | awk '{print $2}' | awk 'BEGIN {FS="|"}{print $1}' | sort | uniq -c | sort -n | tail | sort -nr
.# yes, Cn'P that jazz and tell me you don't see some really interesting output.
.# it's showing you your commands, sorted by repetition. So if you run this command, you can see exactly where
.# you can be reducing keystrokes. ... 
.# I'm going into territory Crockford warned me about. We believe that keystroke reduction is what we need
.# to become better programmers, but he argues that the vast amount of time is spent staring into the abyss!
.# The elephant in the room of the code you already wrote.
.# Either way this is an easy win. Run the command every now and then. Start at the top of your list and keep your keystrokes down 
.# to a minimum by shifting or adding aliases. 
.#
