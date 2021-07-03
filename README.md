# your_grace
administrative console .bashrc 

WARNING!

Installation of this can make it difficult or impossible to get a root bash shell.
Root bash sessions become trapped inside of this admin cli.

Current version is for systems that use "aptitude", so that is a prerequisite for your_grace at this time.

apt-get install -y aptitude

Install your_grace:

sudo su -

chmod +x install_your_grace

./install_your_grace

And then say goodbyte to your regular root bash shell.

Navigate the menus to execute different tasks on the CLI.

Added packages from after your_grace is installed are tracked in /opt/added/packages.list
These are the only packages that can be removed while in your_grace, thus protecting the core system packages in that way.
However the core system packages, and all packages, can also be upgraded with aptitude-based maintenance.

Use on Debian 10 or Ubuntu etc.
