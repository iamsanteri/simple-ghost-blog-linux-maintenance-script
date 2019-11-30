This shell script simplifies the manual maintenance effort of a remote Ghost Blog instance and the accompanying Linux server. 

### Description

It updates for you the following: 

1. Linux packages (Apt Get Update & Upgrade)
2. NPM
3. Ghost CLI
4. Ghost Blog

### Installation

1. Connect to remote server with SSH
2. Create bin folder in the home directory and insert copy of this script
3. Go back to the home directory and create a .bash_profiles file, then paste the export path. Example: "export PATH=$PATH:/home/ [Your user here] /bin"
4. Re-start the terminal 

### How to maintain the server?

1. Open terminal, connect to remote server with SSH
2. Enter login password
3. Run: maintain-server
4. Done, server maintenance complete.