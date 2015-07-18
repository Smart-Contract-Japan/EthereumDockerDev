# Start Ethereum in Docker
latest Docker images for ethereum developer 

### for ubuntu-14.04 if using OSX please using the vagrant VM 
```
sudo apt-get install docker
```
### docker pull ethereum container　include solidity/eth 
```
docker pull syrohei/ethereum:0.9.39
```
### check docker images exist 
```
docker images 
```
### for testnet and private chain


    docker run -it --entrypoint="/usr/bin/geth" syrohei/ethereum:0.9.39 -networkid "10" --datadir="/tmp/eth/60/01" console

### reference javascript API 
https://github.com/ethereum/go-ethereum/wiki/JavaScript-Console  

https://github.com/ethereum/go-ethereum/wiki/Running-in-Docker
  
#### donate
BTC:1BmSux1nsQ6WEqdREX7VCoyQ7dsrwSoK3
