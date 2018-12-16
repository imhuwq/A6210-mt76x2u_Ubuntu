This is a fork of [cyangy/A6210-mt76x2u_Ubuntu](https://github.com/cyangy/A6210-mt76x2u_Ubuntu), tested on ubuntu 16.04.05 with kernel 4.15 on 12/16/2018. My AC55 finaly begins to work(5G).  
Below is the original README.  

---

Thanks  for  [@LorenzoBianconi](https://github.com/LorenzoBianconi)'s great  work，now the USB wireless  dongles  with mt7612u  such as Netgear-A6210  could work on Ubuntu  now. The driver has been tested on Ubuntu16.04 (kernel 4.13.0-43-generic) and it works well.

## Build from Source code

```
$ git clone https://github.com/cyangy/A6210-mt76x2u_Ubuntu.git
$ cd A6210-mt76x2u_Ubuntu
$ make -j $(expr $(nproc) + 1)
$ sudo make install
```
Then pluge  the  USB dongle,Every thing will be ok.
# Known issue
## Just  on  Ubuntu16.04 (kernel 4.13.0-43-generic) ，NetGear A6210
    
1. Only work on 2.4GHz/5GHz STA mode, 2.4GHz/5GHz AP not support yet

THANKS [@LorenzoBianconi](https://github.com/LorenzoBianconi) again.
