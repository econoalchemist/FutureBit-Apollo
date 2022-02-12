# Configuring

SSH connection: user/pass = futerbit/futurebit123

`sudo apt update` then `sudo apt upgrade`

`cd /opt/apolloapi/backend/node`
`sudo nano bitcoin.conf`

add

rpcuser=futurebit

rpcpassword=futurebit

rpcbind=127.0.0.1

rpcbind=192.168.0.11 #(your node)

rpcallowip=127.0.0.1

rpcallowip=192.168.0.12 #(desktop)
