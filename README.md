# TorDDos
TorDDos is a Python tool to automatize DDos attacks to a website from the Tor network.
  
<p align="center"><img src="https://github.com/hack-parthsharma/TorDDOS/blob/master/img/torddos.png" /></p>


## Usage
```

  -h, --help        show this help message and exit
  -t , --target     server to kick-out
  -n , --attempts   number of attempts of attack (default: 5)

```


## How it works
+ Creates a new Tor session.
+ Makes a request to the website you choose as a target.
+ Releases the Tor session, then creates another and request data again to the website.


## Requirements
+ Linux system
+ Python 2.7
+ Tor service
+ requests


## Legal disclaimer
This tool is created for the sole purpose of security awareness and education, it should not be used against systems that you do not have permission to test/attack. The author is not responsible for misuse or for any damage that you may cause. You agree that you use this software at your own risk.
