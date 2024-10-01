## user
```
apt update && apt upgrade -y
```
```
git clone https://github.com/extracepat/Bot
```
```
cd Bot
```
```
screen -S Bot
```
```
bash installnode.sh
```
```
apt install python3.10-venv
```
```
python3 -m venv venv && source venv/bin/activate
```
```
pip3 install -r requirements.txt
```
```
cp sample.env .env
```
```
nano .env
```
```
python3 -m PyroUbot
```
