lxc-list
--------

Simple script to list out the processes running in child LXC containers


	NAME                    | STATUS  | SERVICES
	my.db.host.com          | running | postgres, syslog-ng, sshd, cron, agetty, agetty
	web1.host.com           | running | java, nginx, agetty, syslog-ng, sshd, cron, agetty
	web2.host.com           | running | nginx, syslog-ng, sshd, cron, agetty, agetty

There is some ability to colour different processes differently, but this is
currently hardcoded. Contributions to make it more useful / configurable
are very welcome!

