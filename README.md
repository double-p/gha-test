# Zabbix Infrastructure
This playbook is meant to install all necessary zabbix and its dependant
components:
 - zabbix server
 - zabbix frontend (WebUI)
 - zabbix proxy
 - zabbix agent{,2}

 - postgres DB
 - timescaledb modules
 - pgpool (HA)
 - [pgbouncer (connection pool)]

Configuration of templates/items/.. within zabbix are done
via a different playbook (ref: zabbix_api).

# Dependency
These playbooks are written for ansible@6.
