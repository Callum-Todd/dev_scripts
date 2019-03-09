# Dev Scripts
A Collection of scripts I have created to improve productivity or my workflow.

- `sh_update` - Bash script that copies all the scripts from the local instance of this repository to `~/bin/` 
- `replace` - Bash script that acts as a wrapper to simplifiy a `sed` find and replace
    - Takes 3 arguments: `replace example.c 'struct Node' 'Node'`
        - \<file> - path to file name or '\*.\*'
        - \<string> - string to be replaced
        - \<string> - string to replace with
- `startweb` - Bash script that creates a basic website structure inside a folder
    - Folder name can be passed to script as an argument
