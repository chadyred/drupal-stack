# Make, docker & docker-compose

Make is a Linux bearded tool. It is possible to have a terminal and an isolated space which retrieves all the necessary libraries in order to be able to use all of the Linux commands.
Docker and docker-compose is a virtual applicative tools for handle Deamon needed by our projeect.

#### Linux or Mac

`make install`

#### Cygwin for windows

It is necessary to install Cygwin in order to have make and all the executables under Linux. We can then download the installer
 'setup-x86_64.exe' and follow the wizard classicaly.

Cygwin creates its own path of "c", which allows to isolate the different PATH and we will use these paths to create shortcuts BUT also a '/home/my-user'
 . But you have also all your need windows user at :

Example:

 /cygdrive/c/Users/../ ..

**N.B. :**

Make may not be installed after the end of the installation, but we can use the following with a windows shell :

* cd <download folder>
* setup-x86_64.exe -q --packages = make

#### Terminal

Cygwin has its own terminal. This will be the terminal to use now and we then have access to the / home / user space and a '~ / .bashrc' for shortcuts of command. We will then create a file '~ / .bash_aliases' and edit our '~ / .bashrc' in order to manage our command aliases.

We can also make a 'source ~ / .bashrc' once finished
