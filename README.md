common
======

A bunch of random stuff I want to keep.

common.sh
---------
Common shell functions for various system troubleshooting purposes

Current Md5: 1916fd1e8910ac89dd780f7a9b8fde01

cacti/sshwrapper.sh
-------------
Wrapper for Cacti SSH connections.  Prevents the remote cacti user from performing any actions we don't want them to.  This one is specialized to work with the Percona Monitoring Plugins (Formerly "mysql-cacti-templates").

.ssh/authorized_keys:

    command="/usr/local/bin/sshwrapper.sh" <key> user@host


http://www.cacti.net/

http://www.percona.com/software/percona-monitoring-plugins

cacti/get_mcv.py
----------------
Cacti script to get your Vera(lite) hooked up to the graphing machines!

cacti/get_btcguild.py
---------------------
Cacti script to get your BTC's hooked up to the graphing machines!
