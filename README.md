Meteordev
=========

A simple script to install, update and use the bleeding edge (devel) Meteor version
-----------------------------------------------------------------------------------

Installation
------------
```
git clone git@github.com:alethes/meteordev
/bin/bash ./meteordev/meteordev
```

Usage
-----

The script will download and install the latest Meteor devel version in `~/.meteordev`.
It will also ask your permission to put itself in `/usr/local/bin/meteordev` so it can (presumably) be found in the system's path.

After the script is done running for the first time, it functions as a drop-in replacement for the `meteor` command.
It means you can create, run and manage your apps using the bleeding edge Meteor version:
```
meteor create test-app #or 'meteordev create test-app'
cd test-app
meteordev
```

Why?
----

* It's an easy way to try out and test the upcoming Meteor features and help the Meteor Development Group detect bugs early.
* If you just can't wait for some almost-ready amendments/improvements, then that's the way to go.
