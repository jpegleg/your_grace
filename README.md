# your_grace
administrative console .bashrc 

WARNING!

Installation of this can make it difficult or impossible to get a root bash shell.
Root bash sessions become trapped inside of this admin cli. The desu installer makes it even
more difficult to get a full root shell back.

Current version is for systems that use "aptitude", so that is a prerequisite for your_grace at this time.

apt-get install -y aptitude

Install your_grace:

sudo su -

chmod +x install_your_grace

./install_your_grace

And then say goodbyte to your regular root bash shell.

To more fully lock it away, use the desu version of the install script:

chmod +x desu_install_your_grace

./desu_install_your_grace

Or just disable user access to "su" another way. Without disabling su, a user could get a regular root shell still via "su root -c sh" and so forth.


Say goodbyte to your regular root bash shell, and regular root shells.


Navigate the menus to execute different tasks on the CLI.

Added packages from after your_grace is installed are tracked in /opt/added/packages.list
These are the only packages that can be removed while in your_grace, thus protecting the core system packages in that way.
However the core system packages, and all packages, can also be upgraded with aptitude-based maintenance.
And the added packages feature can by bypassed in the maintenance menu with the interactive aptitude option.

Use on Debian 10 or Ubuntu etc.

Known bugs:

PATH can get temporarily unset with some usage

memory leak from old sleeping instances of your_grace


