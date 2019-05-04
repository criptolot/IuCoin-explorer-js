# IuCoin-Blockchain-Explorer
Block explorer for IuCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon iucoind. It should be accessible from the Internet. Run turtlecoind with open port as follows:
```bash
./IuCoind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11896
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf

Donate: [iUc] iUciUcFABdLDsZ9PFbuTgGKnhSRNgH6Q4MA3M4FVi8V1Z1BhSjwtnUyCN1ZkdXk2YqywHQoEyHQT2xmmN7G7jDCW5pc6Xp1Q38kxg

### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
