
The testROM Project
=====================

Getting Started
---------------

To build testROM from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/source/developing.html).


To initialize your local repository, use this command:

	repo init -u https://github.com/testROM/manifest.git -b alpha

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "userdebug" is default

ENJOY!
