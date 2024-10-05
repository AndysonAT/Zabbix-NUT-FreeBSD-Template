Zabbix-NUT-Template for FreeBSD
===============================

Zabbix Template for NUT(Network UPS Tools) for FreeBSD

Supported UPS: http://www.networkupstools.org/stable-hcl.html


Install
=======

1. Copy ups_status.sh into your externalscripts folder inside your zabbix installation
2. Add execute rights to ups_status.shfor your zabbix user (chown/chmod)
2. Copy userparameter_nut.conf in your zabbix_agentd.d folder your zabbix installation
3. Add read rights to userparameter_nut.conf for your zabbix user (chown/chmod)
4. Import the zbx_import_template.yaml into your WebGUI of Zabbix (Data Collection/Templates/Import)

Info
====
Tested on FreeBSD 14.1, Zabbix 7.0.4 and Eaton UPS

Origin: https://github.com/delin/Zabbix-NUT-Template
