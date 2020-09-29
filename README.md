Clear Nompix18

sudo apt-get update

sudo apt-get upgrade


sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libboost-all-dev libboost-program-options-dev

sudo apt-get install libminiupnpc-dev libzmq3-dev libprotobuf-dev protobuf-compiler libqrencode-dev unzip software-properties-common redis-server npm git screen


sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev



rpcuser=dgfjjhkjhh,h,

rpcpassword=ghgjghjghjghjgj

rpcallowip=127.0.0.1

listen=1

server=1

txindex=1

daemon=1

paytxfee=0.0002

deprecatedrpc=accounts

addresstype=legacy


git clone https://github.com/zone117x/node-open-mining-portal.git nomp

cd nomp

npm update


cp config_example.json config.json


