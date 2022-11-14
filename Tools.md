# grep
## useful flags
* -r recursively. useful when given path is a directory
* -l to only list file names
* -i case insensitive
* -v for reverse grep search to exclude lines that contains the pattern


## To display the number of lines before or after a search string

* use -A n  to display n lines after the match
* Use -B n to display n lines before the match
* Use -C n to display n lines before and after the match

## To limit grep output to a fixed number of matches per file
* -m 2

# To include/exclude file with certain extension
* include: use --include. For example, --include "*.cpp" --include "*h"
* exclude: use --exclude, For example, --exclude "*.h"

# find
To find files match a pattern

classic find in a folder, `find . -name myfile`

## useful flags
* -name to find with case sensitive
* -iname to find with case insensitive
* -exec to have action on found files


# ssh
ssh_known_hosts in /etc/ssh/ssh_known_hosts
# Emacs-based key-bindings for Bash
## move and deletes
* M - f move forward a word
* M - b move backwrd a word
* C - a move to the beginning
* C - e move to the end
* C - u delete to the beginning
* C - k delete to the end
* C - y recover the line
* C - w delete a word 
## ssh-agent
* to display the ssh agent info
* to get pid of ssh agent, please use `eval "$(ssh-agent)"`
* 

