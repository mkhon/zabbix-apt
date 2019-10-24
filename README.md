# Installation

1. Copy userparameter_apt.zabbix_agentd.conf to /etc/zabbix/zabbix_agentd.conf.d/userparameter_apt.conf

2. Install update-notifier-common package (Ubuntu). If you are running Debian you can either install
Ubuntu package or just get /usr/lib/update-notifier/apt-check from it.

3. Import zabbix-apt.xml Zabbix template. The template uses "Agent (active)" type to get raw values -
change the type to "Agent" if you use passive agents.
