Remember that you can always use the command man to read the documentation about any command you like.\
And yes, you can do man man. 

# Search files or directories

##### List the files with specific text in their content 
grep -rl 'SPECIFIC_TEXT' DIRECTORY

# Extract/Compress 

##### Extract a tar file
tar -xvf FILE_NAME\

##### Extract .rar files
unrar x FILE_NAME

# Package managment

##### Install a new package(.deb)
dpkg -i PACKAGE_NAME\

##### Remove a package(.deb)
dpkg -r PACKAGE_NAME

# Docker

# System information

##### Get information about used and unused memory and swap space
free -m\

# Remove files or directories

##### Remove all files inside a directory
rm DIRECTORY_PATH/* 

# Copy files or directories

##### Copy a file
cp SOURCE_FILE DESTINATION_DIRECTORY 

##### Copy a directory and all it's content
cp -r SOURCE_DIRECTORY DESTINATION_DIRECTORY

# Util

##### Open a file or URL 
xdg-open FILE_OR_URL

##### Cool command to kill processes using the pointer to click what you want to kill.
xkill
