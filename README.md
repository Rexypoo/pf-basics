# pf-basics
A basic pf firewall for common services

This configuration file is intended to contain the details necessary to maintain a personal firewall using packetfilter (pf). It is intended to contain some examples of common services and associated rules.

On OpenBSD the pf.conf file belongs in /etc/pf.conf
To restart pf with updated rules use pfctl -f /etc/pf.conf
If you wish to save test configurations in another file change /etc/pf.conf to the location of the desired configuration.
