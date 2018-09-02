# Script for installing StarUML on Fedora

**NOTE**: Right now, Fedora is not my daily usage distro, and I'm not using StarUML anymore (left college and went into the not so obscure path of Sysadmin). So, feel free to update this project, I will gladly receive PR's and even check them in a virtual machine (I still use one with Fedora :) ). Also, for contributions, please use a testing branch, instead of committing directly to master. Thanks!

This script was tested on Fedora 23-26 (even confirmed to be working with CentOS 7! Only make changes to script in case of using yum) . It downloads the version 2.80 of StarUML from its webpage. In case they update their version, please indicate it to me to test a new installation script (or maybe only change its version, hopefully).

NOTE: Only use the uninstall script if you used the installation script here (or if the instructions you've used for installation are similar to the installation script). I can't assure it will work fully if not done that way. Finally, I've adapted the script to download the 32bit version, but I haven't tested it (the procedure looks the same for both, though).

Thanks to Vijaya Simha Reddy Aedavelli, because of the libudev linking detail. The instructions where this script was based on are located at https://staruml.uservoice.com/forums/245359-feature-request/suggestions/7102764-rmp-packages-for-fedora. 

Made by WolfangAukang (2016)
