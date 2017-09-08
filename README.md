# gdrive
it's a gdrive client with linux

this script repo is created by @nanqinlang

original project: https://github.com/prasmussen/gdrive

## usage
command: { install | upload | download }

this script is currently only support the following function:

### install
`bash gdrive.sh install`  
this command is order to `install gdrive client and authenticate gdrive account`

### upload
`bash gdrive.sh upload`  
this command is order to `upload file into gdrive root dir`  
file you want to upload must be in linux's current dir  
upload path is only in gdrive root dir

### download
`bash gdrive.sh download`  
this command is order to `download file from gdrive root dir`  
file you want to download must be in gdrive root dir  
download path is in linux's current dir