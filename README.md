DebConf18 Landing Site
======================

This is the landing site before our full-featured website goes online.  This
website is modified from
[Ananke](https://github.com/budparr/gohugo-theme-ananke) theme and generated
using [Hugo](https://gohugo.io/).

Building the Website
--------------------
The build requisities including git and hugo, please install them.  On Debian
systems it can be installed with following command:

  apt install git hugo

Then, clone this repository:

  git clone https://github.com/medicalwei/debconf18-landing.git

And then clone the git submodule by:

  git submodule init
  git submodule update

Finally, execute the following command to build the website:

  hugo

Live Previewing the Website
---------------------------

Please go through the previous chapter, and run:

  hugo server

The web server for previewing will be displayed in the output of the command.
