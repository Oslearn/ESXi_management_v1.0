# ESXi_management_v1.0
ESXi management v1.0<br>
Programming and idea by : E2MA3N [Iman Homayouni] <br>
Email : e2ma3n@Gmail.com<br>
Website : http://OSLearn.ir<br>
License : GPL v3.0<br>


Dependencies:<br>
	1. sshpass<br>
	2. ping<br>
	3. nc<br>
	4. vmrun<br>
	5. scp<br>
	6. sleep<br>

Install:<br>
	1. cp esxi /usr/bin/esxi<br>

Usage:<br>
	1. esxi -h #help<br>
	2. esxi -s #ESXi Server status<br>
	3. esxi -0 #Shuting down ESXi Server<br>
	4. esxi -6 #Rebooting ESXi Server<br>
	5. esxi -v #Control (start, stop and ...) vms<br>
	6. esxi -u #Upload iso file to datastor<br>

Notes:<br>
	1. set username, password and esxi ip address on script<br>
	2. set esxi upload path on script<br>
