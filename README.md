# All-about-Termux
this repository contains a detailed tutorial about termux, well [what is termux?](https://en.m.wikipedia.org/wiki/Termux), [latest version here](https://f-droid.org/en/packages/com.termux/)

### making a directory
`mkdir <directory name>`

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
`cd <file path>`

#### setting up file and saving it
1. `vim <file path/name>` to open the file
2. `i` to insert texts and edit the file
3. `alt+:+w` to save a file
4. `alt+:+q` to exit file without saving
5. `alt+:+wq` to exit the file by saving it
6. `alt+:+w <file rename>` to rename and save the file
7. `alt+:+wq <file rename>` to rename the file, saving and exiting
