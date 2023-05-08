# PiratePartyV0
Initial implementation of Pirate Party

Local Deployment Guide:
1) Clone repo
|`git clone https://github.com/PirateParty-WIT/PiratePartyV0.git`
2) Install truffle (requires NodeJS) 
|`npm install -g truffle`
3) Install ganache
| `npm install ganache --global`
4) Activate local network
|`ganache -cli`
5) Deploy contracts with Truffle (from the project directory)
|`truffle deploy`