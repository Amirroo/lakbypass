<div align=center>
 
# Aura DDoS

 DDoS Attack Panel includes CloudFlare Bypass (UAM, CAPTCHA, BFM, etc..)<br/><br/>
 Don't attack any websites you don't own it<br/>
 This was created for educational purposes<br/>
 All responsibilities and disadvantages of using this program is for the user.
 

## Language</br>

 <img src="https://img.shields.io/badge/Python-FFDD00?style=for-the-badge&logo=python&logoColor=blue"/></br>
</div>

## Menu
![Aura](![image](https://user-images.githubusercontent.com/96767456/166743576-a1f3d7e7-65dd-447f-ab1b-9ba216f65003.png))

## Methods

```sh
  [Layer 7]
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack with proxy
 - cfreq   | Bypass CF UAM, CAPTCHA, BFM, etc,, with request
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM, etc,, with socket
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
 - sky     | Sky method without proxy
 - http2   | HTTP 2.0 Request Attack 
 = pxhttp2 | HTTP 2.0 Request Attack With Proxy
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack
 - pxraw   | Proxy Request Attack
 - pxsoc   | Proxy Socket Attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  
  [Tools]
 - Dns     | Classic DNS Lookup
 - Geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
```


## Usage on Linux
```sh
You must use Python 3.9 or higher

git clone https://github.com/HyukIsBack/Aura-DDoS.git

Install Python3 modules
 - pip3 install -r requirements.txt  or  pip install -r requirements.txt
Install Chrome (or update it lastest version)
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb

OR
 - python3 setup.py

```

## Example
```sh
Use DDoS Panel   : python3 main.py
Use command line : python3 main.py <method> <target> <thread> <time>
      └──────────> python3 main.py cfb https://example.com 100 30
```

## Contact Developer
```sh
 Telegram: @AuraNetz
```

