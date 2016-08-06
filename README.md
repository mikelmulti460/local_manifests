Local Manifests
=================================


Instructions
---------------

Initializing:

First, create a folder to hold the source code: 

	mkdir ~/cm-12.1

Next..

	cd ~/cm-12.1

Initialize local repository:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1

Also add the local manifests:

    git clone https://github.com/HUAWEI-Y635/local_manifests .repo/local_manifests

Sync up:

	repo sync --force-sync --force-broken
	
-------------
 
_Building_
---------------

First:

	cd ~/cm-12.1

Second:

	. build/envsetup.sh

Third:

    brunch codename
    
Example:

    brunch hwY635
