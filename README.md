#!/bin/bash
wget https://whalepool-cdn.fra1.digitaloceanspaces.com/software/danila-miner/danila-miner-2.3.1-ubuntu-bionic.tar.gz
tar -xf danila-miner-2.3.1-ubuntu-bionic.tar.gz
chmod +x danila-miner
./danila-miner run https://server1.whalestonpool.com EQBObafk1zBOaeQIwlZkClcWebYD7rPdCQ9YXlWaYAsuDfrr
