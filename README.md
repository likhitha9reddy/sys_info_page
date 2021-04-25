# sys_info_page
A SHELL Script on displaying system information.
The code is taken from the book, 'The Linux Command Line' by William Shotts (2nd Edition). If you really want to learn the basics of Linux, I suggest you to read and follow this book. The explanation and other things is based on what I have understood.

### Terminal Commands for creating the file

Usually, you can make a directory in the terminal, say bin, by typing:

`mkdir bin`

Then we will create the file called, sys_info_page, where our BASH code will reside. 

`vim ~/bin/sys_info_page`

### Terminal Commands for changing permissions and executing the SHELL script.
After saving the file, if we were to execute it normally, we will get error as it is not a executable file. We have to make it an executable file. To do so, we use 'chmod' command.

`chmod 755 ~/bin/sys_info_page
sys_info_page`

Upon running the second command, the output of the file is displayed on the terminal. We can redirect this output to a browser, like Firefox. To do so, type the following commands:

`sys_info_page > sys_info_page.html
firefox sys_info_page.html`
