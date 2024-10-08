# 30-Days-SOC-Analyst-Challenge

![image](https://github.com/user-attachments/assets/ef85aaab-308d-447c-8f09-4794ebe75ee7)

## Objectives:
To get practical experience in a SOC Analyst position:
* How to draw a logical diagram
* How to setup and configure ELK
* How to attack, detect and investigate
* How to create alerts and dashboards
* How to setup and integrate ticketing system

Week 1:
* Introduction to ELK
* How to setup ELK
* Ingesting Logs such as Sysmon
  
Week 2:
* Introduction to brute force attack
* How to setup ssh and rdp servers
* Create alerts and dashboards
  
Week 3:
* Introduction to command and control
* How to setup your own C2 server (Mythic)
* Attack our public server

Week 4:
* Introduction to ticketing system
* How to setup and integrate a ticketing system
* Go over how to investigate alerts (high-level)

### Day 1 How to create a logical diagram:

#### Objective: Getting the skills to create logical diagram. 

This is a logical diagram created using the draw.io application. It's a great exercise for improving diagramming skills and serves as a representation of the network map planned for the coming days.

<img src="https://github.com/Matteobarcelona/30-Days-SOC-Analyst-Challenge/blob/main/30%20days%20SOC%20Analyst%20Challenge.drawio.png" alt="30 Days SOC Analyst Challenge Diagram" width="700" height="600" />

### Day 2 ELK stack introduction:

#### Objective: Better understanding of what the ELK stack is and the benefits.

ELK => Elasticsearch, Logstash, Kibana. 

Elasticsearch is a database to store logs (windows logs...) and retrieve the data. It is based on ES-QL => elastic search query language.

Logstash is a pipeline that collect, transform or  filter, datas between applications and output it into Elasticsearch. It can collect data (telemetry) either with beats (file (logs), metrics, packet, winlog, audit, heartbeat (uptime))  or elastic agents (all types of data using 1 unified agent per host)

Kibana is a web console to display the Elasticsearch datas. it helps for visualisation and creating dashboard. 

Benefits of using ELK:
* centralised logging
* flexibility
* visualisations
* scalability to larger environment
* ecosystem (many integrations)

### Day 3 Elasticsearch Setup:

#### Objective: Better understanding of what the ELK stack is and the benefits.
