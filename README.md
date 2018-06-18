[//]: # ($FrauBSD: mping/README.md 2018-06-18 18:17:38 +0000 freebsdfrau $)

# mping

Ping multiple hosts

mping is a utility for pinging multiple hosts. It is written in shell with
minimal dependencies (awk, date, getconf, head, host, ping, sleep, sort, stty,
tr, uname, and xargs). It also has a feature to keep watching the given hosts
and alert to any changes in uptime. Works on Mac OS X, Linux, and FreeBSD.
Supports playing custom sounds on Mac OS X with afplay utility.

## Foreword

The following is required before using `git commit` in this project.

> `$ .git-hooks/install.sh`

This will ensure the FrauBSD keyword is expanded/updated for each commit.

