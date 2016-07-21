Nik Collection on GIMP
===

Installation script to install Nik Collection for use with GIMP (2.9 & 2.10) and as a standalone app.

Note:

* Tested on Ubuntu 16.04 with Wine Staging v1.9.14 using Nik Collection v1.2.11, and GIMP v2.9.5 (from git).
* Make sure that Windows OS version set for wine is set to XP.
* Depending on your system specs the apps can take some time to start.

Issues:

* GIMP will complain with the message 'Incompatible type for "RichTIFFIPTC"; tag ignored' after using some of the apps. This is because both open a TIF file and give back a high quality JPEG file, but the file has JPEG extension. If you click ok, the error will go away and everything will work.
