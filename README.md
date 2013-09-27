## Sample python application

### Setting up Vagrant

Visit http://downloads.vagrantup.com/tags/v1.3.3 and download the appropriate
version. Once this is installed, simply type clone this repository and  type
`vagrant up` into your command line.  This will start a virtual machine with
all the libraries you need installed to start writing your Flask application.

### Running Flask

Once you have started Vagrant, type `vagrant ssh` to ssh into your virtual
machine.  The folder `/vagrant` is mirrored on your own machine and you can
access any files from your  own machine from this folder.  So type
`cd /vagrant` and then `python application.py` to start the sample Python
application I have loaded.  You should be able to load up localhost:5000 in
your browser and see Hello World.

#### Happy Hacking!
