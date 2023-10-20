# python312-debian-repo
Setup for python 3.12 (.deb).

Download the binary (.deb) file from the releases section and then 
navigate to the folder where you saved the file, then open a terminal and run:

`dpkg -i ./python3.12*.deb`

In the terminal there will be an extra choice to change the install location to 
/usr instead of /usr/local, but this will overwrite the existing python at /usr/bin 
which some of your apps may depend on.

>If you have suggested edits, please feel free to fork and make a pull request.


# Package Installer

If you are using the  package installer app (a.k.a Gdebi Package Installer), 
make sure to expand the terminal to show the above options such that you choose 
whatever is best for you.

![gdebi](https://github.com/DanielHuey/python312-debian-repo/assets/33962088/d6cfe710-faac-461d-8828-a8af0c38d4c8)
