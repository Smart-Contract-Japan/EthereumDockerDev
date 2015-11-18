# Start Ethereum in Docker
latest Docker images for ethereum developer 

first. this command tasks require to vmware virtual machine . please install following commands

## for ubuntu-14.04 if using OSX please using the vagrant VM . installing  vagrant and virtual box
```
wget https://raw.githubusercontent.com/syrohei/dotfile/master/install_osx.sh
```
```
chmod 644 ./install_osx.sh
```
```
sudo sh ./install_osx.sh
```
### second. running up vagrant 
```
sudo vagrant up
```
``` 
ssh vagrant
```
### installing docker
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
