# Tauro Technologies BSP Platform

To get the BSP you need to have repo installed and use it as:

Install the repo utility:

$: mkdir ~/bin

$: curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

$: chmod a+x ~/bin/repo

Download the BSP source:

$: PATH=${PATH}:~/bin

$: mkdir ~/taurotech-bsp-yocto

$ cd ~/taurotech-bsp-yocto

$ repo init -u https://bitbucket.org/taurotech/manifests.git -b master

$ repo sync -j4

At the end of the commands you have every metadata you need to start work with.

To start a simple image build:

$: MACHINE=<machine> DISTRO=<distro> source ./setup-environment <build directory>

$: bitbake core-image-base

You can use any directory to host your build.

The source code is checked out at taurotech-bsp-yocto/sources.



