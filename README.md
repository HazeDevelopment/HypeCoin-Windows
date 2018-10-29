# HypeCoin-Windows

Binary Update 2018/10/29

How to run HypeCoin in Windows?

1. create a folder named "config" inside the folder "HypeCoin"

2. cd to folder "config", create a text file named "Hype.conf"

3. input the follows in "Hype.conf"

#Seeds
seed-node=149.28.207.69:16966

seed-node=149.28.168.138:16966

seed-node=149.28.165.6:16966

seed-node=207.148.86.20:16966


#Port options
p2p-bind-port=16966

rpc-bind-port=16969

#Data Directory

data-dir=~/.HypeCoin/

rpc-bind-ip=0.0.0.0

4. run HypeCoin with this command "HypeCoind.exe --config-file ./configs/hype.conf"

5. run the wallet with this command "simplewallet.exe --config-file ./configs/hype.conf"
