mretok
======

Bandwitdh data display

Usage: mretok <options> [interface]
Options:
  -h,  --help	  this
  -V,  --ver	  version and license info
  -d		  show total downloaded data [auto]
   -db		   show total downloaded data [bytes]
   -dk		   show total downloaded data [KiB]
   -dm		   show total downloaded data [MiB]
   -dg		   show total downloaded data [GiB]
   -dt		   show total downloaded data [TiB]
  -u		  show total uploaded data [auto]
   -ub		   show total uploaded data [bytes]
   -uk		   show total uploaded data [KiB]
   -um		   show total uploaded data [MiB]
   -ug		   show total uploaded data [GiB]
   -ut		   show total uploaded data [TiB]
  -g		  show total amount of data with IP address
   -ge		   also display external IP (via dyndns.com)

If [interface] is not set, 'eth0' will be used by default.

Example:
 mretok -d wlan0
will display total downlaoded data on wlan0 interface.

Note: For -ge option you need to have 'lynx' installed!
