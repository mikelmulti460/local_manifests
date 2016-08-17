Local Manifests
=================================


Instructions
---------------

Initializing:

First, create a folder to hold the source code: 

	mkdir ~/rr

Next..

	cd ~/rr

Initialize local repository:

    repo init -u https://github.com/ResurrectionRemix/platform_manifest.git -b lollipop5.1

Also add the local manifests:

    git clone https://github.com/mikelmulti460/local_manifests .repo/local_manifests

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

    brunch hwY550
