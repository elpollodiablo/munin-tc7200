munin-tc7200
============

Simple munin scripts for graphing TC7200 cable modem channel properties

Copy or symlink tc7200_* to /etc/munin/plugins, and add some configuration 
to /etc/munin/plugin-conf.d/munin-node:

    [tc7200_*]
    env.routerip 192.168.0.1
    env.routeruser admin
    env.routerpassword admin

then restart munin-node.

Created for firmware version  - your cable modem configuration or
firmware may be different, if it doesn't work, please send me the source of 
your /status/connection-upstream.asp and /status/connection-downstream.asp
pages.

Greetings go out to UPC Austria again for providing for the necessary 
motivation.
