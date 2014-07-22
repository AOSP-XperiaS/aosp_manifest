AOSP for Xperia S (nozomi) and Xperia Acro S (hikari)
=================================

Getting Started
---------------

**1. initialize the repo:**

    repo init -u git://github.com/AOSP-XperiaS/aosp_manifest.git -b aosp-4.4

**2. sync repo:**

    repo sync -c

**3. build:**

    - source build/envsetup.sh
    - lunch aosp_nozomi-userdebug *for nozomi*
    - lunch aosp_hikari-userdebug *for hikari*
    - make otapackage
