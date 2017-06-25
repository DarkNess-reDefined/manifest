[<center><img src="https://github.com/DarkNess-reDefined/reDefinition_documentation/raw/graphics/dnd.png" height="100%" width="100%;"/></center>](https://github.com/DarkNess-reDefined)

DarkNess reDefined
==================
As you all know "Darkness is the entity that gives light a sense".
Our theme is light and glossy, Which gives you the fastest and smoothest android experiences without any lags.


Getting Started
---------------
To initialize your local repository using the our trees, use a command like this: [7.1.2]

    repo init -u https://github.com/DarkNess-reDefined/manifest.git -b n7x

Then to sync up:
---------------
    repo sync --force-sync --force-broken --no-clone-bundle -jxxx (ur choice dude)


Some important stuffs for your build:
-----------------

```bash
   *You have two choices for root
   For SU : Use "export WITH_SU=true" or add "WITH_SU=true" in tree.
   For magisk : Use "export WITH_ROOT=true" or add "WITH_ROOT=true" in tree.
   *You have two choices for equalizer
   For AudioFX : Use "export WITH_AUDIOFX=true" or add "WITH_AUDIOFX=true" in tree.
   For DSPManager : Use "export WITH_DSPMANAGER=true" or add "WITH_DSPMANAGER=true" in tree.
```

Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch dnd_device_codename-userdebug
  mka darkness
```
Credits
-------
* [**LineageOS (Base)**](https://github.com/LineageOS)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**OmniROM**](https://github.com/omnirom/)

