# zabbixdocker
env_vars знаходиться на  https://git.rdr-it.io/docker/zabbix/-/tree/main/env_vars




як робить
sudo git clone https://git.rdr-it.io/docker/zabbix.git .
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
cd env_vars - тут змінюєш
sudo docker-compose pull
sudo docker-compose up   піднімає можна  sudo docker-compose up -d
