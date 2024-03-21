# Dotfiles 

Clone the repo to your home folder. 
Symlink the files in this ~/dotfiles folder to ~ folder. 
Be sure to use the absolute path

`ls -nfs /Users/diede/dotfiles/.tmux.conf /Users/diede/.tmux.conf`

The flags added to the symlinking command offer a few additional benefits:
-s creates a symbolic link instead of a hard link
-f continues with other symlinking when an error occurs (not needed here, but useful in loops)
-n avoids symlinking a symlink (same as -h for other versions of ln)
