# grep
## Common flags
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

# ssh
ssh_known_hosts in /etc/ssh/ssh_known_hosts

## ssh-agent
* to display the ssh agent info
* to get pid of ssh agent, please use `eval "$(ssh-agent)"`
* 
