INTRODUCTION

This is the source code of ptracker and stracker (or in short: sptracker), an app suite for 
Assetto Corsa. Note that the actual development currently takes place in a private svn 
repository, which is essentially the same as the git repository provided here. Please respect 
the license as provided in LICENSE.txt. 

BEFORE YOU START MODIFYING

I was hesitating for a long time to open up the source code for this. The main reason for this
was the concern that there might be a lot of forks of ptracker and stracker with different 
network protocols and that not enought care will be taken to make the protocols backwards and
forward compatible. 

Now that I see, that my time for contributing to ptracker and stracker will be more limited
than in the past, I think it is fair to open up the source code, so others might want to 
jump in and help.

I can just appeal to the coders to consider contributing to the project instead creating a fork. 
I'm willing to accept patches if they are mature enough to be integrated and integrate these 
patches into the mainstream project with the usual experimental/stable releases.

GETTING STARTED

See in DEPENDECIES.txt for a list of dependencies. I suggest to use virtualenv to create the 
ptracker and stracker environment for the python 3.3 interpreter. Most if not all dependencies
should be easily installable with pip. Please use the specified versions to avoid troubles.

To use ptracker directly from the python interpreter, you need to edit the file ptracker.py and 
adapt the path to your virtual python directory.

CONTACTING THE AUTHOR

The original author Neys is contactable as user never_eat_yellow_snow1 at the Assetto Corsa forums 
(http://www.assettocorsa.net/forum/index.php) or as user Neys at the RaceDepartment forums
(http://www.racedepartment.com/forums/).


INSTALLATION DEPENDENCIES

pip3 install simplejson
pip3 install pygal
pip3 install cherrypy
pip3 install acplugins4python
pip3 install bottle
pip3 install apsw
pip3 install psycopg2-binary

OR

apt install python3-pip
apt install python3-bottle
apt install python3-psycopg2
apt install python3-dateutil
apt install python3-simplejso
apt install python3-pygal
apt install python3-cherrypy3
apt install python3-apsw
