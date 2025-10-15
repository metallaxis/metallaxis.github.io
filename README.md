# metallaxis.github.io
Website exersice for university

I do not know if this is intended but in the byte6 the user cannot unzip the file in the home folder,
i worked around this by copying the file in a temporary /tmp/temp folder and unzipping it there.

For the the byte7 i had to do something else as well, i added in my .ssh/config the hostname and username and then scp the file using scp temp:~/byte7.tar.gz ~ in order for me to be able to extract the file
