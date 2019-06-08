# Freetype_Library
testing upload


------------------------------------Prepare System before copying  !!!  ----------------------------------------


sudo dpkg --add-architecture i386
sudo apt-get update

sudo apt-get install build-essential

sudo apt-get install gcc-multilib g++-multilib \
lib32z1 lib32stdc++6 lib32gcc1 \
expat:i386 fontconfig:i386 libfreetype6:i386 libexpat1:i386 libc6:i386 libgtk-3-0:i386 \
libcanberra0:i386 libpng12-0:i386 libice6:i386 libsm6:i386 libncurses5:i386 zlib1g:i386 \
libx11-6:i386 libxau6:i386 libxdmcp6:i386 libxext6:i386 libxft2:i386 libxrender1:i386 \
libxt6:i386 libxtst6:i386





-----------------------------------------------Copy as below!!!!!   ---------------------------------------------


For doing freetype

Copy lib32 folder to " modelsim_ase " folder.

   Add lib32 folder address to {bin/vsim } file as      

     export LD_LIBRARY_PATH=${dir}/lib32

   underneath " dir=`dirname $arg0`  ".

----------------------------------------------Add this addon also --------------------------------------------------

PLease change linux_rh60 to linux in {bin/vsim} near vco selection
And do ./bin/vsim















