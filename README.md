-----------------------------------------------------------------------------


-----------------------------------------------------------------------------
Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/darkinfusion/manifest.git 
```

Then to sync up:-
================

```bash
    repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

Start the build:-
=================

```bash
  . build/envsetup.sh
  lunch darkinfusion_<devicecodename>-userdebug
  mka bacon -jx
```
-----------------------------------------------------------------------------



----------------------------------------------------------------------------



---------------------------------------------------------------------------------
