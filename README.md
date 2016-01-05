Role Name
=========

Install Kafka-monitor as a docker image.

Requirements
------------

Role Variables
--------------
```
---
# defaults file for kafka-monitor
kafka_monitor_state: reloaded
zk_kafka_path: "localhost:2181"

```

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: kafka-monitor
           zk_kafka_path: "zk-host:2181/kafka"

License
-------
BSD

Author Information
------------------
Krzysztof Zarzycki 
