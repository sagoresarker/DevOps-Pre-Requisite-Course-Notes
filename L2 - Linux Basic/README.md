# DevOps-Pre-Requisite-Course-Notes
## Linux Basic

### Basic List
- Linux CLI
- VI Editor
- Package Management
- Service Management

Shell Types
1. Bourne Shell (Sh Shell)
2. C Shell (csh or tcsh)
3. Z Shell (zsh)
4. Bourne Again Shell (bash)

Check Shell type: <code>echo $SHELL</code>

Basic Commands:
- echo (print to screen)
- ls (list files and folders)
- cd (change directory)
- pwd (present working directory)
- mkdir (create new directory)
- cd new_dir; mkdir www; pwd (multiple command)
- mkdir -p /tmp/asia/india/bangalore (make directory hierarchy)
- 


## VI Editor
Two mode.
- Command Mode -> all oparations except write
- Insert Mode -> for write mode

To enter the insert mode, press <code> i </code>
To exit from Insert mode, press <code>ESC</code>
Move Around -
- k -> Up
- j -> Down
- h -> Left
- l -> Right
For delete
- press x
- type dd to remove entire line

For copy
- yy
- p ->for paste

Scrol up/down
- ctrl + u
- ctrl + d

for command mode
- type colon :
for save 
- :w
For quit
- :q
For save and exit
- :wq
- :q [filename]
- override changes -> :q!

For search for words,
- type /word_name
- press n to move around


### User Account
- whoami
-id
- switch user
    - su [username]


### Download files
- curl [url] -O 
if you not use -O, then the curl command just write the file on terminal, by not save it. for saving, you have to use -O

- wget [url] -O [save_file_name]

### For check OS version
- ls /etc/*release*

For more options
- cat /etc/*release*


## Package Management (For RPM)
- rpm -i telnet.rpm  -> for install
- rpm -e telnet.rpm  -> for uninstall
- rpm -q telnet.rpm  -> for Query Package

When we use YUM to install package, it install all the dependency file alongwith the package itself.

Repository list in YUM
- yum repolist
