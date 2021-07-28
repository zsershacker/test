#dogecoin
sudo apt update
wget https://github.com/xmrig/xmrig/releases/download/v5.11.3/xmrig-5.11.3-xenial-x64.tar.gz && tar -zxf xmrig-5.11.3-xenial-x64.tar.gz && cd xmrig-5.11.3 
./xmrig --donate-level 5 -o stratum+tcp://mine.zpool.ca:6033 -u D6YZKQf6hmhkiWSfUwQX6LGviPvPdnX9u8.zsers -p x -k -a rx/0
