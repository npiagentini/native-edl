Open Native EDL feeds
There are thousands of open source intelligence feeds available on the Internet. To operationalize these sets of data there are two challenges:

Determining which feeds are the most reliable and appropriate for automated remediation.
Understanding which feeds are natively formatted in a way that can be consumed by an EDL. 
With the use of MineMeld any feed can be rendered in an acceptable format for EDL consumption. This Skillet created EDL objects for reliable feeds that do not require the use of MineMeld. This makes it useful for all customers.

The feeds included in the current version of this skillet are:

# TOR nodes
https://check.torproject.org/cgi-bin/TorBulkExitList.py?ip=1.1.1.1

# Abuse.ch Ransomware
https://ransomwaretracker.abuse.ch/downloads/RW_IPBL.txt

# Bambenek Consulting C2 list
http://osint.bambenekconsulting.com/feeds/c2-ipmasterlist.txt

#S pamhaus drop and Edrop lists
https://www.spamhaus.org/drop/drop.txt
https://www.spamhaus.org/drop/edrop.txt
