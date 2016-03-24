#######################################################################################################################################
#  Contents of Project                                                                                                                #
#######################################################################################################################################

CONTENTS OF THIS FILE
---------------------
   
 * Introduction
 * Configuration

INTRODUCTION
------------
This github repository contains files that display edits made to specific directory files that allow for Nagios Core to monitor CPU Usage,Memory Usage, Disk Usage, System Uptime, apache2 availability, and wordpress site availability.

CONFIGURATION
-------------

For these files to work, nagios3, nagios-plugins, snmp, snmpd, MIB downloader, mysql, apache, upstart, and vim have to be downloaded and installed in your Ubuntu system. The files in this repositiory have the following addresses:

/etc/init/nagios.conf (Service to be run with Upstart)

/etc/snmp/snmp.conf

/etc/snmp/snmpd.conf

/etc/nagios-plugins/config/dns.cfg

/etc/nagios3/conf.d/services_nagios2.cfg
