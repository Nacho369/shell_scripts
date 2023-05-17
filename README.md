# Scripts For ALX SE Programme

### The **cx** script
This script create a file, changes it permission to be executable by all users and opens the file in the `VIM` editor.

> **cx filename**

### The **cxb** script (Shell Script)
This script create a file, with the line `#!/bin/bash` in it, changes the permission to be executable by all users and opens the file in the `VIM` editor.

> **cxb filename**

### The **cxp** script (Python Script)
This script create a file, with the line `#!/usr/bin/python3` in it, changes the permission to be executable by all users and opens the file in the `VIM` editor.

> **cxp filename**

### The **cxc** script (C Script)
This script create a file, with basic C language file structure in it, and opens the file in the `VIM` editor.

> **cxc filename**

### The **gacp** script (Git Script)
This script add, commit with a the user message and push to the remote server. It takes in a parameter for the commit message which would be immediately after the name od the script. e.g;

> **gacp  "Your commit message here"**

### The **addssh** script
This script authenticate your local repository to push your files from your local repository to your remote repository. It takes in two parameters. The first one is the file name of your private ssh key and the second is the url of your remote repository. e.g;

> **addssh  ssh-key  "url of your remote repo"**

:round_pushpin::round_pushpin: **NOTE: To be able to run your script without the prefix `sh`, `bash` or `./`, you would have to add the location of this script to your path. Else you would need the prefix. Below are the steps.**

:round_pushpin::round_pushpin: **NOTE: You can change the default editor to open your file by changing it in the script file.**

### Prequisite
#### Clone the repository.
```
git clone https://github.com/Nacho369/shell_scripts.git
```
#### Edit your `.bashrc` file

In your `home` or `root` directory, open your `.bashrc` file with any terminal editor and type the command below in it. When done save and quit from the file. Then exit the termainal and open it again.
```
export PATH="$PATH:~/shell_scripts"
```
### After these, you can now run the script without the prefix.
