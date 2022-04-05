** NETGEAR ReadyNAS Statistics **
Created by Prolag ( http://blog.igut.fr )

The script fully supports SNMP v1/v2/v3.
	
The script will display the fan speed and temperature (Box & Hard Disk) of NETGEAR ReadyNAS (NV+, NVx, Pro, 1100, 2100, 3200)

The script is not tested with ReadyNAS 1100 and 3200 (need testeur...)

-Requirements- 

Need a ReadyNAS with RAIDiator >= 4.2.8 for x86 (NVx, Pro, 2100, 3200)
Need a ReadyNAS with RAIDiator >= 4.1.7 for Sparc (NV+)

-Installation-

1) Import the graph templates of your model (NV+, NVx, Pro, 2100)
2) In the options of your device, add the Associated Graph Templates for your model (NETGEAR - ReadyNAS XXX - NAS FANS or NAS Temperature)
3) Create graphs
4) Wait for the pretty graphs and enjoy.


-Changelog-

2.1 - Fixed a problem when there is no hard drive (negative temperature)
	- There a 1 fan and 1 internal probe into the NVx
2.0 - Use directly OID value (no php script)
	- Add support of x86 ReadyNAS (NVx, Pro, 2100, 3200)
	
1.0 - Initial release (Support of ReadyNAS NV+)
