#### 1. Connect to Node Via Putty ( Putty 통해서 서버 연결 )

#### 2. Go to GTTC Build-Bin Directory by running the code Below (노드 경우 이동 - 아래 명령 실행)

```
cd ~/go/src/github.com/TTCECO/gttc/build/bin/
```

#### 3.1 Run Node in Background (노드 배경에서 시작 - 아래 명령 실행)
```
nohup sudo ./gttc --datadir unknown01/ --rpc --rpcaddr "0.0.0.0" --rpcport "1000" --rpccorsdomain "*" --rpcapi "admin,db,eth,net,web3,miner,personal,alien" --port 30301 -unlock 't0759365bcdee07c250e85247c2258a5c186b1b741' --password pwd.txt --mine > output.unknonw01 &
```


#### 3.2 Run Node in Foreground (화면에 시작 - 아래 명령 실행)
```
sudo ./gttc --datadir unknown01/ --rpc --rpcaddr "0.0.0.0" --rpcport "1000" --rpccorsdomain "*" --rpcapi "admin,db,eth,net,web3,miner,personal,alien" --port 30301 -unlock 't0759365bcdee07c250e85247c2258a5c186b1b741' --password pwd.txt --mine 
```


