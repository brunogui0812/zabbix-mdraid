# zabbix-mdraid
Linux mdraid monitoring for Zabbix

# resources/items/triggers

- Auto Discovery md devices
- RAID status (item)
- Problem on RAID (trigger)
- Rebuilding RAID (trigger)
- Unknown Error on RAID (trigger)

# roadmap

- Install script

# installation

- create a sudo entry to execute script
- copy conf/mdadm.conf to /etc/zabbix/zabbix.agent.d/
- copy scripts/ to /etc/zabbix/scripts
- import template

# contributors

Bruno Guilherme Souza (me)
