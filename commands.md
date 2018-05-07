First of all remember, you can always use the command man to read the documentation about any command you like.\
And yes, you can do man man.\ 
Also remember that you can use / to search text along the documentation. After hitting ENTER, use n to move to the next occurrence and N to move to the previous one.\

##### Wanna extract a tar file
tar -xvf FILE_NAME\
-x extract this file\
-v list files processed\
-f you are going to pass a file name

##### Install a new package(.deb)
dpkg -i PACKAGE_NAME\
-i install

##### Remove a package(.deb)
dpkg -r PACKAGE_NAME

#### Get information about used and unused memory and swap space
free -m\
-m display the values in megabytes

The output is gonna be something like this:

>               total        used        free      shared  buff/cache   available
> Mem:           1888         817         322         111         748         966
> Swap:          1326           3        1322

The row mem gives information about random access memory(RAM). Now, what is RAM?\
RAM is a volatile type of memory, which means that stored information is lost if power is removed. It stores data and machine code currently being used, and that can be accessed or written a lot faster than in a Non-volatile memory like a hard drive.

 - total: amount of RAM the computer has.
 - used: amount of RAM that is being used.
 - free: amount of RAM that is unused.
 - shared: amount of memory that may be simultaneously accessed by multiple programs with an intent to provide communication among them or avoid redundant copies.
 - buff/cache:  amount of memory being used by buffers and cache.

Whats the difference between cache memory and a buffer?\
A buffer is a temporary location to store data for a particular application and this data is not used by any other application. For example, when you try to send burst of data through network, if your network card is capable of sending less data, it will keep these huge amounts of data in buffer so that it can send data constantly in lesser speeds. In other hand Cache is a memory location to store frequently used data for faster access. Other difference between a buffer and a cache is that cache can be used multiple times where as buffer is used single time. And both are temporary store for your data processing.

 - available: Estimation of how much memory is available for starting new applications, without swapping.

The row Swap gives information about swap space. Now, what is that?\
Swap space is used when the amount of physical memory (RAM) is full. If the system needs more memory resources and the RAM is full, inactive pages in memory are moved to the swap space. While swap space can help machines with a small amount of RAM, it should not be considered a replacement for more RAM. Swap space is located on hard drives, which have a slower access time than physical memory.
