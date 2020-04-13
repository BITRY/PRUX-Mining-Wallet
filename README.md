PRUX-Coin integration/staging tree
=====================================

What is PRUX?
-------------
PRUX is a very fast, maybe the fastest ltc-Fork and is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Prux uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. PRUX Core is the name of open source
software which enables the use of this currency. 

For more information, as well as an immediately useable,
see https://bitcointalk.org/index.php?topic=2064953.new#new


License
-------
PRUX is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.


PRUX COIN INFORMATION
---------------------
Hash Algorithm : Scrypt
Typ : Proof-of-Work
Block Time : 9sec
Miner Reward : 0.00959499 PRUX
Actual Reward : 0.004797495 PRUX
Difficulty Retarget : 5 - 12 Hours
Mined Block Confirmation : 274
Total Supply : After 90 Years only ~104k 
Premine = ZERO


Development Process
-------------------
The `master` branch is regularly built and tested, but and is guaranteed to be
completely stable.
The contribution workflow is described in official BT-Thread


NEXT STEPS
----------
1) Adding tor as Standard ( We can use some code from Torcoin )
2) Better Network connectivity, better node links. 
3) More Exchanges and pools
4) We will holding so much of Satoshis Original Code as possible, but we need small change for future.
5) We have to watch on the used ram of prux daemon, maybe in future we have to find a way to strip pruxcoind, less ram ussage. We got the biggest Satoshoi modell  blockchain, now or in future. This is one of the difficulties that the PURX blockchain will become very big and we need solutions.
6)
7)
8)
..
22) Update PRUX-Core and integrade merged mining, if somebody can help with code and testing, your welcome.
planed in future, but only think about.


INSTALL INFORMATION
-------------------
LINUX / UBUNTU 14.04 BUILD READ FILE HERE -------->>>>  /prux/doc/build-unix.txt


POOL LIST
---------
https://prux.mastermining.net/site/mining


EXCHANGES
---------
https://ex.xbts.io/#/market/PRUX_BTS    ( Sould be ready End of April 2020 )


UBUNTU 14.04 BUILD NOTES
------------------------
sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install qt4-dev-tools libqt4-dev libqt4-core libqt4-gui

sudo apt-get install build-essential

sudo apt-get install libssl-dev

sudo apt-get install libdb4.8-dev if not work try sudo apt-get install libdb-dev

sudo apt-get install libdb4.8++-dev  if not work try sudo apt-get install libdb++-dev

sudo apt-get install libqrencode-dev

sudo apt-get install libboost1.48-dev   if not work try  sudo apt-get install libboost-dev

sudo apt-get install libboost1.48-all-dev  if not work try  sudo apt-get install libboost-all-dev


BUILD
-----

cd PRUX-COIN-master

qmake "USE_UPNP=-"

make                        (or  make -j2  , 2 core or the fast way or turbo with -j8)

cd src

make -f  makefile.unix USE_UPNP=-      (or -j2  ,the fast way or turbo with -j8)


if error can help

cd src

chmod +x leveldb/build_detect_platform

againThis is one of the difficulties that the PURX blockchain will become very big and we need solutions.



Running
-------

./prux-qt -addnode=77.239.55.52:9595

or

src/./prux -addnode=77.239.55.52:9595


NODES
-----

addnode=77.239.55.52:9595

addnode=50.225.198.67

addnode=62.109.27.153

addnode=78.46.18.218

addnode=78.154.170.70

addnode=50.232.104.35

addnode=109.195.103.14

addnode=217.115.116.200

addnode=51.81.254.26

addnode=142.44.133.95

addnode=77.239.55.52

Testing
-------

You are all welcome to help and improve PRUX-Core



