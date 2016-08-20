Local Manifests
=================================


Instructions
---------------

Initializing:

First, create a folder to hold the source code: 

	mkdir ~/cm-13.0

Next..

	cd ~/cm-13.0

Initialize local repository:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-13.0

Also add the local manifests:

    git clone https://github.com/mikelmulti460/local_manifests .repo/local_manifests

Sync up:

	repo sync --force-sync --force-broken
	
-------------
 
_Building_
---------------

First:

	cd ~/cm-13.0

Second:

	. build/envsetup.sh

Third:

    brunch codename
    
Example:

    brunch hwY550

