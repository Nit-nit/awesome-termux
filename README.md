# Awesome termux tutorial
this repository contains a detailed tutorial about termux, well [what is termux?](https://en.m.wikipedia.org/wiki/Termux) and [latest version here](https://f-droid.org/en/packages/com.termux/)!!

# Basic commands usage

commands | usage
---- | ----
first command | this table is coming soon

### making a folder or directory
`mkdir <.../path/directory-name>`<br>
here `mkdir` means make directory (folder)

### making a file
`touch <.../path/file-name>`

### deleting a folder/directory or file
`rm -r <file path>`

### getting access to internal/shared storage
`termux setup storage`

### opening files from internal storage
1. install vim text editor `pkg install vim`
2. open shared storage `vim ~/storage/shared/`

### entering a directoy and running commands inside it to make files and more directories inside it
1. `cd <.../path/directory-name>` to open a directory and using it as current directory
2. `cd` to get out of the current directory again
3. `vim ./` to open the current directory and inspect it, you can see the list of all the folders and files this directory contains using this command

### setting up a file and saving it using vim
1. `vim <.../path/file-name>` to open the file
2. `i` to insert texts and edit the file
3. `alt`+`:`+`w` to save a file
4. `alt`+`q!` to exit file without saving
5. `alt`+`:`+`wq` to exit the file by saving it
6. `alt`+`:`+`w` <file rename>` to rename and save the file
7. `alt`+`:`+`wq` <file rename>` to rename the file, saving and exiting

### killing a process and stopping some action which is in progress
`ctrl`+`4`

### closing the tab and exiting the app
`ctrl`+`d`
