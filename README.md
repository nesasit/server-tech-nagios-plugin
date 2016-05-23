# server-tech-nagios-plugin

This is a nagios plugin to monitor ServerTech PDUs.

It will use the check\_snmp plugin to look at the following things:
* Power Usage (by tower)
* Temperature (by sensor)
* Humidity (by sensor)

It will also have thresholds for the above items.
