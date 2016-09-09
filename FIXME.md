FIXME for Nagios Barclamp
==========================

* currently some require packages are missing in the default distribution of the SUSE Cloud:
- `nagios` (required by Nagios server)
- `nagios-www` (required by Nagios server)
- `monitoring-plugins-nagios` (required by Nagios server and client)
- `monitoring-plugins-nrpe` (required by Nagios server and client)

* Issues with PHP of the Web UI of Nagios
- PHP dependency is missing
- it seems that PHP7 is installed, but PHP5 is configured

All required packages can be found in the [server monitoring](https://build.opensuse.org/project/show/server:monitoring) project
