This shell script simplifies the manual maintenance effort of a remote Ghost instance and the server. 

### Description

It updates for you the following: 

1. Linux packages (Apt Get Update & Upgrade)
2. NPM
3. Ghost CLI
4. Ghost Blog

It additionally creates a backup of the Ghost content directory. 

### Installation

1. Connect to remote server with SSH
2. Create bin folder in the home directory and insert copy of this script 

You can insert the script with a following command: "scp your-local-directory/maintain-server root@XXX.XXX.XXX.XXX:../home/your-remote-directory/bin/maintain-server"

### How to maintain the server?

1. First of all back up from the frontend (Admin)
2. Open terminal, connect to remote server with SSH
3. Enter login password
4. Run: sudo bash bin/maintain-server
5. Done, your server maintenance is complete.
