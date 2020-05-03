### Compilation tested on ubuntu 19.10 and 20.04 LTS

package to install:
dh-autoreconf
libboost-all-dev
libusb-1.0.0-dev
libssl-dev
cmake
libprotobuf-dev
protobuf-c-compiler

You might need to build protobuf-compile:
https://wiki.odroid.com/odroid-c2/application_note/software/android_auto#build_protobuf-compiler_30

git clone -b master https://github.com/thomas-lepage/aasdk.git
mkdir aasdk_build
cd aasdk_build
cmake -DCMAKE_BUILD_TYPE=Release ../aasdk
make
