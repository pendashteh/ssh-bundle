# ssh-bundle
Organise your ssh config and maintain ssh configs inside each project.

```
undies API version 4

Parameters:
__sshdir="/home/user/.ssh"

Available tasks:
 - create    # 
 - enable    # @arg bundle directory @does add the ssh config under bundle to ~/.ssh
 - fixpermissions# @does fix permissions on ssh config files.
 - help      # @arg task @does declare task implementation
 - install   # 

Usage:
 $ ssh-bundle [__param=value] [task]
```
