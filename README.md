# установить

apt-get install git python python-nfqueue python-scapy

git clone https://github.com/lumpov/nodevfee.git

rc.local:

python /home/user/nodevfee/nodevfee.py &

exit 0

# обновить
git pull origin master

# проверка

ps -ax | grep python
