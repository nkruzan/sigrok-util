required packages for build:
sudo apt install -y ant autoconf autoconf-archive automake build-essential check cmake default-jre doxygen g++ gcc git git-core libavahi-client-dev libboost-dev libboost-filesystem-dev libboost-serialization-dev libboost-system-dev libboost-test-dev libftdi1-dev libglib2.0-dev libglibmm-2.4-dev libgpiv3-dev libhidapi-dev libieee1284-3-dev libqt5svg5-dev libqwt-qt5-dev libtool libusb-1.0-0-dev libvisa-dev libzip-dev make nettle-dev pkg-config python-gi-dev python3-dev python3-numpy python3-setuptools-git qtbase5-dev qttools5-dev qttools5-dev-tools swig libsigrok* libnettle8 libieee1284-3-dev libhidapi-dev python-gi-dev ruby 

to build:
git clone https://github.com/nkruzan/sigrok-util.git
cd sigrok-util
git checkout build-nov2024
cd cross-compile/android
./sigrok-cross-android prepare
./sigrok-cross-android 
