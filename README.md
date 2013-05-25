android_local_pantech_ef44s
======================

Local Manifest for pantech ef44s devices

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Make a build directory:

	mkdir Andoid (or whatever name you choose)
	cd Android (or the name  you chose)
	mkdir .repo/local_manifests

To initialize your local repository using the Cyanogemod manifest, use commands like these:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-10.1

    curl -L -o .repo/android_local_pantech_ef44s/ef44s.xml -O -L https://raw.github.com/UISS-Dev-Team/android_local_pantech_ef44s/cm-10.1/ef44s.xml
 
    	( or Download: https://github.com/UISS-Dev-Team/android_local_pantech_ef44s/blob/cm-10.1/ef44s.xml
		and place it in ~/Android/.repo/local_manifest.xml (or ~/'name you chose'/.repo)

Then to sync up:

    repo sync
