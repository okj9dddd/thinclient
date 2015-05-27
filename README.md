# DESCRIPTION
This set of scripts is intended to create GNU/Linux image, that can be booted via network and run from memory, without mounting rootfs via NFS/iSCSI/CIFS/..., like [this](https://help.ubuntu.com/community/DisklessUbuntuHowto). Based on Debian/Ubuntu.

# FEATURES
 * Easyly add any software from reach Debian/Ubuntu repositories: browser, recorder for video cam, media player, etc. This is not so easy for thin clients, using their own package base, like [ThinStation](http://sourceforge.net/apps/mediawiki/thinstation/index.php?title=Main_Page).
 * Overlays(file archives) can be mounted over root filesystem, allowing different thin stations to have different configs/software, without building many different images
 * Home folder may be mounted via NFS, so changes are saved.

# DOCUMENTATION

[Wiki](https://github.com/selivan/thinclient/wiki)
