## Sample python application

### Setting up Vagrant

To set up Vagrant, you first need to install VirtualBox
from https://www.virtualbox.org/wiki/Downloads.  Visit
http://downloads.vagrantup.com/tags/v1.3.3 and download the appropriate
version. Once this is installed, simply type clone this repository and  type
`vagrant up` into your command line.  This will start a virtual machine with
all the libraries you need installed to start writing your Flask application.

If you would like to add other software to your Vagrant box, edit the file
`bootstrap.sh`.  Run `vagrant provision` to re-run the bootstrap script
on Vagrant.

### Running Flask

Once you have started Vagrant, type `vagrant ssh` to ssh into your virtual
machine.  The folder `/vagrant` is mirrored on your own machine and you can
access any files from your  own machine from this folder.  So type
`cd /vagrant` and then `python application.py` to start the sample Python
application I have loaded.  You should be able to load up localhost:5000 in
your browser and see Hello World.

### Wish List

* Full-featured app
* Put the app in its own folder
* Other development environments?

Happy Hacking!
