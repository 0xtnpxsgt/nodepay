# nodepay

- You must need to buy a VPS for running Allora Worker
- You can buy from : Contabo
- You should buy VPS which is fulfilling all these requirements : 
```bash
Operating System : Ubuntu 22.04
CPU: Minimum of 1/2 core.
Memory: 2 to 4 GB.
Storage: SSD or NVMe with at least 5GB of space.
```

## Tools and components required
- Nodepay Account| Register: https://app.nodepay.ai/register?ref=XufJ19oYRId1omA
- Proxies Static Residental | FREE 10 PREMIUM PROXIES
- VPS (OPTIONAL) and Python3


## Setup Tutorial
- Open Nodepay and login to dashboard
- Press F12 or CTRL + SHIFT + I
- Select Console
- Find type localStorage.getItem('np_token') and press enter
- The text that appears is your nodepay token and copy the code

## Installation

Install Python
```bash
apt install python3 python3-pip -y
```

Clone project repository
```bash
git clone https://github.com/0xtnpxsgt/nodepay.git && cd nodepay
```

Install requirements:
```bash
python -m pip install -r requirements.txt
```

Install requirements:
```bash
python -m pip install -r requirements.txt
```

## Edit Proxy
- Replace the proxies example in proxies.txt to your own proxies, please use only 10 proxies with proxies http only.
```bash
nano proxies.txt
```

## Run the bot
```bash
python3 run.py
```
if not successful Please use the second script.
Use this script if you getting errors like Error during API call: 403 Client Error: Forbidden for url

## Run for bypass server:
```bash
python3 run-bypass.py
```

# Notes
- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- One account only can connect with 10 Proxies
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.







