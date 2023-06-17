# mint-pixelcase
This script mint pixelcase NFT https://zk-mint.pixelcase.io/ in Zksync Era network. Needs only ETH for gas, mint = free. Deadline: 24.06.2023

## Prerequisites

- Add private keys to private_key.txt (one line - one key)
- You might change min/max delay between accounts in mint-pixelcase.py

## Installation

Run commands like this:

```
apt install python3-pip, git
git clone https://github.com/Kizliak/mint-pixelcase
cd mint-pixelcase
pip install -r requirements.txt
```

Add private keys:

```
nano private_key.txt
```

Run script
```
python3 mint-pixelcase.py
```
