<p align="center">
<img src="https://github.com/bananadroid/android_manifest/blob/14/banner.png?raw=true" > 
</p>

---------------------------------------------------------------------------------------------------------
BananaDroid
====================
Another cherry-picking ROM, developed by an usual person, nothing special


To initialize your local repository, use this command:
-----------------------------------------------------

    repo init --depth=1 --no-repo-verify -u https://github.com/HinohArata/android_manifest-BNN.git -b 14 --git-lfs -g default,-mips,-darwin,-notdefault

To sync the repository, use this command:
-----------------------------------------

    repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --retry-fetches=5 -j$(nproc --all)

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch banana_<devicecodename>-userdebug
    m banana

---------------------------------------------------------------------------------------------------------

Special thanks to All ROM Developers in this community

---------------------------------------------------------------------------------------------------------

Join our [**Telegram Group**](https://t.me/bananadroid) and follow our [**Telegram Channel**](https://t.me/bananadroidchannel)

Thank you!

---------------------------------------------------------------------------------------------------------
