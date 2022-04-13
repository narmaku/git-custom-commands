# git-custom-commands
Repository with custom GIT commands that can be used to automate manual tasks or as shortcuts for common command combos, etc. 

## Basics
1. All scripts must start with `git-` prefix. What follows the prefix is the actual name of the command that you want to use.
2. They cannot end with .sh or similar. Example: `git-lazycheckout`.
3. Scripts must be accessible from $PATH. This can be done by:
    - Modifying your .bashrc (or similar  to your shell/terminall)
    - Installing (copying or moving) the scripts to any of the valid defualt $PATH locations (less recommended)

### How to use your custom git commands
Once the scripts are in the right location, in the new terminal session (to take new scripts from $PATH) you can just invoke them with `git <your_command>`.
