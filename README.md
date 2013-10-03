### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

## Install

1. git clone git://github.com/huyng/bashmarks.git
2. make install
3. source **~/.local/bin/bashmarks.sh** from within your **~.bash\_profile** or **~/.bashrc** file

## Shell Commands

    mark <bookmark_name>        - Marks the current directory as "bookmark_name"
    j <bookmark_name>           - Jumps (cd) to the directory associated with "bookmark_name"
    mark_print <bookmark_name>  - Prints the directory associated with "bookmark_name"
    mark_delete <bookmark_name> - Deletes the bookmark
    mark                        - Lists all available bookmarks
    
## Example Usage

    $ cd /var/www/
    $ mark webfolder
    $ cd /usr/local/lib/
    $ mark locallib
    $ mark
    $ j web<tab>
    $ j webfolder

## Where Bashmarks are stored
    
All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.
