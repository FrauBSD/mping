[//]: # ($FrauBSD: mping/README.md 2018-07-03 01:59:47 +0000 freebsdfrau $)

# mping

Ping multiple hosts

mping is a utility for pinging multiple hosts. It is written in shell with
minimal dependencies (awk, date, getconf, head, host, ping, sleep, sort, stty,
tr, uname, and xargs). It also has a feature to keep watching the given hosts
and alert to any changes in availability. Works on Mac OS X, Linux, and
FreeBSD. Supports playing custom sounds on Mac OS X with afplay utility.

Quickly get status on one or more hosts using ping. Automatically takes
advantage of multiple CPUs and will ping multiple hosts in parallel.

Watch changes in ping status with "-d" for differential mode to alert you when
changes take place.

Use shell expansion features such as 192.168.0.{1..254} to quickly scan for
unused IP addresses (if applicable).

## Foreword

The following is required before using `git commit` in this project.

> `$ .git-hooks/install.sh`

This will ensure the FrauBSD keyword is expanded/updated for each commit.

