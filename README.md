munin-mikrotik-scripts
======================
Munin data collection scripts (plugins) to monitor MikroTik devices.

I have updated and fixed some of the outdated munin scripts/plugins from http://wiki.mikrotik.com/wiki/Munin_Monitoring, mainly updating OID's, datastructures or a complete rewrite.

The scripts are written in php or perl. Check the scripts to see which modules or classes you need to install for them to function properly. The scripts themselves communicate with the MikroTik devices thought several protocols, either SNMP, telnet or PHP API.

All munin plugins have been developed and tested on Munin 2.0.24 and MikroTik RouterOS 6.24.

Please use the bugtracker @ https://github.com/acidsploit/munin-mikrotik-scripts/issues to leave any comments, issues or feedback.

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

