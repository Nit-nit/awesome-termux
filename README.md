# All-about-Termux
this repository contains a detailed tutorial about termux, well [what is termux?](https://en.m.wikipedia.org/wiki/Termux), [latest version here](https://f-droid.org/en/packages/com.termux/)

### making a directory
`mkdir <.../path/directory-name>`

### making a file
`touch <file path, file name and format>`

### deleting a file
`rm -r <file path>`

### getting access to internal/shared storage
`termux setup storage`

### opening files from internal storage
1. install vim text editor `pkg install vim`
2. `vim ~/storage/shared/`

### entering a file and running commands in it
1. `cd <.../path/directory-name>` to open the file and using it current directory
2. `cd` to getting out of the file again
3. `vim ./` to open a file in current directory

### setting up a file and saving it using vim
1. `vim <file path/name>` to open the file
2. `i` to insert texts and edit the file
3. `alt+:+w` to save a file
4. `alt+:+q` to exit file without saving
5. `alt+:+wq` to exit the file by saving it
6. `alt+:+w <file rename>` to rename and save the file
7. `alt+:+wq <file rename>` to rename the file, saving and exiting

### closing the tab and exiting the app
`ctrl+d`
