[Chronos Open Source Project](http://www.infamousdevelopment.com/)
====================================


Download the Source
===================

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.

Initializing Repository
-----------------------

Init core trees:

$ repo init -u https://github.com/ChronosRom/chronos_manifest.git -b cr-4.4

sync repo :

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    . build/envsetup.sh && time brunch jflte


You can also build (and see how long it took) for specific devices like this:

    chmod 755 build.sh
    ./build.sh -d jflte

Remember to `make clobber` every now and then!
