# MQL-CopyTrade

Copy Trade System for MetaTrader 5 Client based on MQL script.

## Environment

- Windows 7 above (recommend)
- MetaTrader 5 Client  
- [ZeroMQ](https://github.com/zeromq)  
- [ZeroMQ for MQL](https://github.com/dingmaotu/mql-zmq)  
- Notice: Not work well with Netting account when parting close a position.

## How to install
- Follow install intruction ZeroMQ for MQL on [ZeroMQ for MQL](https://github.com/dingmaotu/mql-zmq) for MQL5.
- Copy LvApublisherServer to Expert folder of MQL5 Client of a server.
- Copy LvApublisherClient to Expert folder of MQL5 Client of a client.
- Run only one instance of LvApublisherServer expert in MT5 program.
- Run only one instance of LvApublisherClient expert in MT5 program.

## Features

- Remote Publisher and Subscriber (Based on IP address)  
- New Order (Market Order, Pending Order)  
- Modify Order (TP, SL)  
- Close Order (Normal Close, Partial Close)  
- Custom Trading Symbol between Publisher and Subscriber  

The Publishers do not need to log in with a trading password, just log in and using the investor password.  

## License

Copyright (c) 2024 Le Van An.  
MQL-Zmq Copyright (c) Ding Li [ZeroMQ for MQL](https://github.com/dingmaotu).  

Code released under the MIT license.

## TODO

- Support custom copy ratio per symbol
