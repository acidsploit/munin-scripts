munin-scripts
=============

My collection of updated munin data collection scripts (plugins).

These are mainly existing scripts that were outdated or lacking functionality and were in need of an update.

All munin plugins have been developed and tested on Munin 2.0.24.

Please use the bugtracker @ https://github.com/acidsploit/munin-scripts/issues to leave any comments, issues or feedback.

Updated plugins:
- /munin-mikrotik-scripts/mikrotikcpu__
	- hostname
- /munin-mikrotik-scripts/mikrotikdiskspace_
	- hostname
- /munin-mikrotik-scripts/mikrotikifrate_
	- hostname_ifname
- /munin-mikrotik-scripts/mikrotikmemory_
	- hostname
- /munin-bitcoind-scripts/bitcoind_
	- balance
	- connections
	- paytxfee
	- relayfee
	- transactions
	- block_age
	- difficulty
	- score
	- blocks

New pugins:
- /munin-mikrotik-scripts/mikrotikuptime_
- /munin-mikrotik-scripts/mikrotiksensors_
	- temperature
	- voltage
