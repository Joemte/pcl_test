# pcl_test

Ubuntu安装pcl，并配置cmake


1、安装各种依赖包

sudo apt-get install g++

sudo apt-get install cmake cmake-gui

sudo apt-get install doxygen

sudo apt-get install mpi-default-dev openmpi-bin openmpi-common

sudo apt-get install libflann1.8 libflann-dev

sudo apt-get install libeigen3-dev

sudo apt-get install libboost-all-dev

sudo apt-get install libvtk6-dev libvtk6.2 libvtk6.2-qt

sudo apt-get install ‘libqhull*’

sudo apt-get install libusb-dev

sudo apt-get install libgtest-dev

sudo apt-get install git-core freeglut3-dev pkg-config

sudo apt-get install build-essential libxmu-dev libxi-dev

sudo apt-get install libusb-1.0-0-dev graphviz mono-complete

sudo apt-get install qt-sdk openjdk-9-jdk openjdk-9-jre

sudo apt-get install phonon-backend-gstreamer

sudo apt-get install phonon-backend-vlc

sudo apt-get install libopenni-dev libopenni2-dev


2、解压PCL1.9源码包

cd pcl-pcl-1.9.1/

mkdir build

cd build/

cmake -

DPCL_DIR=/usr/local/share/pcl-1.9 …

注意这个会默认安装到/usr/local目录下，而pcl1.7默认是在/usr/include和/usr/lib下的


3、编译

make

sudo make install
