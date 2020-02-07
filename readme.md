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
3. Go back to the home directory and create a ".bash_profile" file, then paste the export path. Example: "export PATH=$PATH:/home/[Your user here]/bin"
4. Re-start the terminal 

You can insert the script with a following command: "scp your-local-directory/maintain-server root@XXX.XXX.XXX.XXX:../home/your-remote-directory/bin/maintain-server"

### How to maintain the server?

1. Open terminal, connect to remote server with SSH
2. Enter login password
3. Run: maintain-server
4. Done, your server maintenance is complete.