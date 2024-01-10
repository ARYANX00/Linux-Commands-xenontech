To make it Run You just have do certain Steps

Step1: cd internsctl
Step2: chmod +x internsctl (This make the file runnable)

then Use the commands : by using ./internsctl 

a manual is listed bellow:


# CPU Information
./internsctl cpu getinfo

# Memory Information
./internsctl memory getinfo

# User Commands
## Create a New User
./internsctl user create <username>
## List All Regular Users
./internsctl user list
## List Users with Sudo Permissions
./internsctl user list --sudo-only

# File Information
## Get File Information
./internsctl file getinfo <file-name>
## Get Specific File Information
### Size
./internsctl file getinfo --size <file-name>
### Permissions
./internsctl file getinfo --permissions <file-name>
### Owner
./internsctl file getinfo --owner <file-name>
### Last Modified Time
./internsctl file getinfo --last-modified <file-name>

# Options
## Help
./internsctl --help

## Version
./internsctl --version


