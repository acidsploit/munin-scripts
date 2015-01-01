munin-mikrotik-scripts
======================
Munin data collection scripts (plugins) to monitor mikrotik devices.

I have updated and fixed some of the outdated munin scripts/plugins from http://wiki.mikrotik.com/wiki/Munin_Monitoring, mainly updating OID's, datastructures or a complete rewrite.

The scripts are written in php or perl. Check the scripts to see which modules or classes you need to install for them to function. The scripts themselves communicate with the MikroTik devices thought several protocols, either SNMP, telnet or PHP API.

Updated plugins:
- mikrotikcpu_
- mikrotikdiskspace_
- mikrotikifrate_
- mikrotikmemory_

New pugins:
- mikrotikuptime_
- mikrotiksensors_
	- temperature
	- voltage

Dependencies:
- PHP:
	- routeros_api.class.php
- Perl:
	- Net::SNMP

