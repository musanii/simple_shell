# simple_shell
This project encompasses a simple unix shell developed from scratch. A shell is an interractive Command Line Intepretter that utilizes the comandline. So basically  we developed a shell that would make it easy to utilize a commandline interface(CLI).
Users can type basic defined sets of >commands e.g "ls" to list files in a current directory,"rm" to remove or delete a file from a directory, etc. This operations will be run effectively in the Operating system. The mode of interaction with CLI is slightly different from the Graphical User iInterface where a user can esily tap on an icon and a folder or an application opens. Depending on different users  others may prefer using the command line to instruct the operating system because they may view typing being fun and quicker than clicking and dragging.

## Synopsis
This project repository holds all the code necessary for  funtioning of our simple shell. Currently ,the shell  can handle the executions of  functions available in the environment variable  $PATH alongside the existing full paths if found. Examples of commands supported by our simple shell are-:
*ls (bin/ls), echo, which, whereis* etc

### Builtins
Below builtins have also been included in our simple shell
* **env** prints environmental variables (Usage: *env*)
* **cd** change directories (Usage: *cd [-][~][path]*)
* **unsetenv** removes an envrionmental variable (Usage: *unsetenv name value*)
* **exit** closes the shell (Usage: *exit [status]*)
* **setenv** creates or modifies an environmental variable (Usage: *setenv name value*)
## System calls / Functions used 
read, signal, malloc, free, getcwd, chdir, access, execve, wait, write, exit

## Environment
Language: C
Operatin System: Ubuntu 20.04
Compiler: gcc 
Style: Betty style
