## Plex PMS Munin Scripts

A rough and ready set of munin scripts for the Plex PMS (developed and used
using the ReadyNAS PMS).

These are mostly used for testing issues found/discussed in the Plex linux forum.

Check out to /usr/share/munin/plugins/plex-pms-munin and symlink to /etc/munin/plugins (similar to standard plugins).

You'll need to run most of them as the same user as Plex - which on the ReadyNAS is root. Add the following to /etc/munin/plugin-conf.d/munin-node:

    [plex*]
    user root

