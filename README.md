# MQTT Sample Script
##### This script allows you to send messages to test.mosquitto.org using python

# Installation
##### Using pip3
```bash
pip3 install -r requirements.txt
```

# Usage
#### To subscribe to everything please use # (eg. stephen/#)
#### Subscriber
```bash
python3 mosquittoClient.py $TOPIC $QOS
```

#### Publisher
```bash
python3 mosquittoSender.py $TOPIC $QOS $PAYLOAD
```

 
