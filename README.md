# Linux-Bash

#!/bin/bash

Use "exit" to exit the shell script.

To run the script, have to prepend "./" before the script name. This is a security feature as if this prefix not there, then any malware program sharing the name of an existing command would run first.

Better to create a "bin" directory under home folder and place the scripts in that so only the author can execute those scripts. Add that location to $PATH. In that case no need of prepending "./" to the shell file.

Any script put in /usr/local/bin can be run by any user logged into the system. Any program not managed thru a package manager ends up here.

~/.profile is one of the configuration files.

# Variables
time = "$(date)"
echo "Time is: $var1"
echo $BASH_VERSION
echo $HOME

# Questions
What are the possible data types? What are the limitations on computations?
What's the delimiter of each line of code inside the script?
What are most commonly used re-defined variables?
