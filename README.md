# how to build on a pc
clone the repo, install required host packages.

~~~~
cd openwrt
git checkout xxxx
./add_feeds.sh
make world -j16

~~~~

# install python
~~~~
opkg update
opkg install python python-pip python-dev python-openssl gcc curl 

~~~~
