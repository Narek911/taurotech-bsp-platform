Tauro Technologies Yocto BSP
===============================

Supported boards
----------------

   . Rock960

Quick Start Guide
-----------------

Once you have downloaded the source of all projects, you will have to
call:

$: . ./setup-environment <build directory>

After this step, you will be with everything need for build an image.

Contributing
------------

To contribute to the development of this BSP and/or submit patches for
new boards please send the patches against the respective project as
informated bellow:

The following layers are included on this release:

 * poky: base build system and metadata
   Path: sources/poky
   GIT: git://git.yoctoproject.org/poky
   Mailing list: https://lists.yoctoproject.org/listinfo/yocto

 * meta-openembedded: extra packages and features
   Path: sources/meta-openembedded
   GIT: git://git.openembedded.org/meta-openembedded
   Mailing list: http://lists.linuxtogo.org/cgi-bin/mailman/listinfo/openembedded-devel
   Note: Use [meta-oe] in subject to easy the processing

  * meta-python2: legacy python2 support after EOL
   Path: sources/meta-python2
   GIT: git://git.openembedded.org/meta-python2
  
   * meta-rockchip: Yocto BSP layer for the Rockchip SOC boards
   Path: sources/meta-rockchip
   GIT: https://github.com/rockchip-linux/meta-rockchip
