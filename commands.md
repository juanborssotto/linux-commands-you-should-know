Remember that you can always use the command man to read the documentation about any command you like.\
And yes, you can do man man. 

# Search

##### List the files with specific text in their content 
grep -rl 'SPECIFIC_TEXT' DIRECTORY





# Extract/Compress 

##### Extract a tar file
tar -xvf FILE_NAME\

##### Extract .rar files
unrar x FILE_NAME

##### Compress a file/directory as tar.gz 
tar -czvf NAME_OF_ARCHIVE.tar.gz PATH_TO_DIRECTORY_OR_FILE





# Package managment

##### Install a new package(.deb)
dpkg -i PACKAGE_NAME\

##### Remove a package(.deb)
dpkg -r PACKAGE_NAME





# Docker

##### List only running containers
docker ps

##### List all containers
docker ps -a





# System information

##### Get information about used and unused memory and swap space
free -m\

##### Report file system disk space usage
df





# File/Directory managment

##### Remove all files inside a directory
rm DIRECTORY_PATH/* 

##### Copy a file
cp SOURCE_FILE DESTINATION_DIRECTORY 

##### Copy a directory and all it's content
cp -r SOURCE_DIRECTORY DESTINATION_DIRECTORY

##### Create a new empty file
touch FILENAME.FILE_EXTENSION

##### Give permissions to write, read and execute a file to anyone
chmod 777 FILE_NAME

##### Give permissions to write, read and execute all the content of directory to anyone 
chmod -R 777 DIRECTORY 

##### Sort a file in ascending order
sort FILENAME

##### Sort a file in descending order
sort -r FILENAME

##### Redirect terminal output to file
SOME_COMMAND > FILENAME  

##### Append terminal output to file
SOME_COMMAND >> FILENAME  

##### Print the name of the current/working directory
pwd

##### Print last n lines of file
tail -n NUMBER_LINES FILENAME

##### Print first n lines of file
head -n NUMBER_LINES FILENAME





# Util

##### Open a file or URL 
xdg-open FILE_OR_URL

##### Cool command to kill processes using the pointer to click what you want to kill.
xkill

##### History of commands
history

##### Search a specific text in history commands
history | grep -i SPECIFIC_TEXT

##### Shutdown computer
shutdown -h now

##### Suspend computer
systemctl suspend

##### Print or write user/login name associated with the current user ID to the standard output.
whoami

##### Change your user password
passwd
