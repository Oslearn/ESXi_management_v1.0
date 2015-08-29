# ESXi_management_v1.0
ESXi management v1.0
Programming and idea by : E2MA3N [Iman Homayouni] <br>
Email : e2ma3n@Gmail.com
Website : http://OSLearn.ir
License : GPL v3.0


Dependencies:
	1. sshpass
	2. ping
	3. nc
	4. vmrun
	5. scp
	6. sleep

Install:
	1. cp esxi /usr/bin/esxi

Usage:
	1. esxi -h #help<br>
	2. esxi -s #ESXi Server status
	3. esxi -0 #Shuting down ESXi Server
	4. esxi -6 #Rebooting ESXi Server
	5. esxi -v #Control (start, stop and ...) vms
	6. esxi -u #Upload iso file to datastor

Notes:
	1. set username, password and esxi ip address on script
	2. set esxi upload path on script
