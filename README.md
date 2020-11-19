# lib_skt_lte
sparrow 보드에 장착된 SKT LTE 모듈의 LTE 품질을 측정하는 라이브러리 프로세스
## Install dependencies
### MQTT-broker
```
$ wget http://repo.mosquitto.org/debian/mosquitto-repo.gpg.key
$ sudo apt-key add mosquitto-repo.gpg.key
$ cd /etc/apt/sources.list.d/
$ sudo wget http://repo.mosquitto.org/debian/mosquitto-buster.list 
$ sudo apt-get update
$ sudo apt-get install -y mosquitto
```
### Python Library
#### mqtt
```
$ pip3 install paho-mqtt
