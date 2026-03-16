# Setup Instructions

## 1. Install Cowrie Honeypot
Clone Cowrie repository:

git clone https://github.com/cowrie/cowrie.git

Start Cowrie:

cd cowrie
bin/cowrie start

## 2. Install Elasticsearch

sudo apt install elasticsearch
sudo systemctl start elasticsearch

## 3. Install Kibana

sudo apt install kibana
sudo systemctl start kibana

## 4. Install Filebeat

sudo apt install filebeat

Configure Filebeat to send Cowrie logs to Elasticsearch.

## 5. Visualize Logs

Open Kibana in browser:

http://localhost:5601

Create dashboards to visualize attacker activity.
