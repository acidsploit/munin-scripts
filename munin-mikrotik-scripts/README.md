munin-mikrotik-scripts
======================
Munin data collection scripts (plugins) to monitor MikroTik devices.

I have updated and fixed some of the outdated munin scripts/plugins from http://wiki.mikrotik.com/wiki/Munin_Monitoring, mainly updating OID's, datastructures or a complete rewrite.

The scripts are written in php or perl. Check the scripts to see which modules or classes you need to install for them to function properly. The scripts themselves communicate with the MikroTik devices thought several protocols, either SNMP, telnet or PHP API.

All munin plugins have been developed and tested on Munin 2.0.24 and MikroTik RouterOS 6.24.

Please use the bugtracker @ https://github.com/acidsploit/munin-scripts/issues to leave any comments, issues or feedback.

Updated plugins:
- /munin-mikrotik-scripts/mikrotikcpu_
	- hostname
- /munin-mikrotik-scripts/mikrotikdiskspace_
	- hostname
- /munin-mikrotik-scripts/mikrotikifrate_
	- hostname_ifname
- /munin-mikrotik-scripts/mikrotikmemory_
	- hostname

New pugins:
- /munin-mikrotik-scripts/mikrotikuptime_
	- hostname
- /munin-mikrotik-scripts/mikrotiksensors_
	- hostname_temperature
	- hostname_voltage
- /munin-mikrotik-scripts/mikrotikwificlients_
	- hostname_ifname



Dependencies:
- PHP:
	- routeros_api.class.php
- Perl:
	- Net::SNMP

