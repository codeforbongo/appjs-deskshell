appjs-deskshell
===============

SDK for building desktop applications using html5 / css / js. A simple json file with a .desk extension launches
a desktop app with a frontend built using web technologies. The application can communicate with a backend
built using familiar server scripts like nodejs or php. This backend allows you to access databases,
write to disk and do whatever you need outside of the browser sandbox.


Windows:
========

The quickest way to start using deskshell for windows is to download the installer. This includes an example app
that also serves as documentation and guide for the project. http://appjs.delightfulsoftware.com/deskshell/.
To develop the code git clone the repository and then read the bin/win/readme.txt file for further details.

Mac:
====
On mac git clone the repository, cd to bin/mac and then run

tar xvfz deskshell.mac.tgz

This will give you a deskshell app bundle, click on it to register .desk files. After first run you should be able 
to click .desk files to launch applications.

Mac port instructions are here: https://github.com/sihorton/appjs-deskshell/tree/master/bin/mac

Linux:
============

Take a look at bin/linux folder. We will release an installer in the future.



See http://appjs.delightfulsoftware.com/ for my previous work on packaging appjs for windows and linux.
