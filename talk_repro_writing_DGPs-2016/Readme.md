#README
#######


To execute the syntax for compiling the markdown source code to pdf, 
pandoc is needed. Make sure it is installed.

Next, execute the make file. Note that it is not a Gnu Make file, but
just a simple text file with a shell script.

Either copy the syntax to the command line (shell/bash/terminal), or
execute the .sh file. In Unix-type OS (Mac OS, Linux), you need to
make the file executable using this commmand:

    chmod +x make_pandoc.sh


Then, execute the file using this syntax:

    sh make_pandoc.sh


Note that all files need to be in the working directory.