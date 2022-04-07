# Ubuntu
```wget https://github.com/xmrig/xmrig/releases/download/v6.17.0/xmrig-6.17.0-focal-x64.tar.gz
tar -xf xmrig-6.17.0-focal-x64.tar.gz
cd xmrig-6.17.0
wget https://raw.githubusercontent.com/Tokaaaage/a/main/miner.sh
chmod 777 miner.sh
cd /etc/systemd/system
wget https://raw.githubusercontent.com/Tokaaaage/a/main/miner.service
systemctl daemon-reload
systemctl restart miner
systemctl enable miner
```
