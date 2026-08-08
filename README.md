```console
$ ssh abdurrahman@kartal
```
```log
[    0.000000] Linux version 5.15.0-kartal (abdurrahman@istanbul)
[    0.000001] Command line: root=/dev/coffee ro quiet splash
[    0.412009] Initializing cgroup subsys motivation
[    0.883141] ACPI: early table checksum verification disabled
[    1.204558] loading module  javascript.ko ...... ok
[    1.204901] loading module  typescript.ko ...... ok
[    1.205334] loading module  css.ko ............. ok (7 warnings)
[    1.209887] loading module  sleep.ko ........... FAILED (busy)
[    1.884120] hub 1-0:1.0: 47 browser tabs detected, 47 retained
[    2.550013] systemd[1]: Reached target Caffeinated.
[    2.771902] kartal login: _
```

```console
$ cat /etc/motd
```
```
   _                  _           _
  | | __  __ _  _ __ | |_   __ _ | |
  | |/ / / _` || '__|| __| / _` || |
  |   < | (_| || |   | |_ | (_| || |
  |_|\_\ \__,_||_|    \__| \__,_||_|

  kartal  (n.)  Turkish for "eagle".
                also: this machine.
                also: me.

  Last login: today, from a tab that should have been closed.
```

```console
$ man abdurrahman
```
```troff
ABDURRAHMAN(1)              User Commands             ABDURRAHMAN(1)

NAME
       abdurrahman - web developer, Turkey

SYNOPSIS
       abdurrahman [--coffee] [-v] [--no-meetings] <problem>

DESCRIPTION
       Reads a vague requirement from stdin and writes a working
       interface to stdout. Latency varies with caffeine.

OPTIONS
       -v, --verbose
              Explain the architecture. Twice. Unprompted.

       --coffee
              Required. Without it the process starts but does
              not respond to signals.

       --no-meetings
              Increases throughput by roughly 400%.

EXIT STATUS
       0      it works
       1      it works on my machine
       418    I'm a teapot, and it's 3 AM

SEE ALSO
       git-blame(1), stackoverflow(7), rm-rf(1)  [DEPRECATED]

BUGS
       Refactors code that already worked. Known. Won't fix.
```

```console
$ ps aux --sort=-%mem
```
```yaml
USER   PID  %CPU  %MEM  STAT  START   COMMAND
abd    001  91.2  47.3  R     2019    side-project --never-finish
abd    042  44.0  22.1  R+    08:14   css --center-a-div --retry
abd    137  18.6   9.4  S     11:30   learn --everything --at-once
abd    256   6.1   4.8  S     yester  refactor --scope=creeping
abd    404   0.0   0.0  Z     ?       sleep 28800          [defunct]
root   666   ---   ---  D     ?       node_modules --uninterruptible
```

```console
$ df -h /skills
```
```yaml
Filesystem       Size  Used  Avail  Use%  Mounted on
javascript        47G   41G   6.0G   87%  /skills/js
css               32G   30G   2.0G   94%  /skills/css
html              28G   27G   1.0G   96%  /skills/html
php               24G   17G   7.0G   71%  /skills/php
git               16G   11G   5.0G   69%  /skills/git
figma              8G  2.4G   5.6G   30%  /skills/design
tmpfs            512M  511M   1.0M   99%  /skills/patience

df: '/skills/regex': permission denied
```

```console
$ git log --oneline --author=abdurrahman
```
```gitattributes
a1b2c3d  please work
4e5f6a7  final FINAL i mean it this time
8b9c0d1  revert "final v2"
2f3a4b5  final v2
6c7d8e9  final
0a1b2c3  fix typo
d4e5f6a  fix typo in the typo fix
7b8c9d0  it was a missing semicolon. it is always a semicolon.
1e2f3a4  do not touch this function, nobody knows why it works
5a6b7c8  initial commit
```

```console
$ crontab -l
```
```crontab
# m  h        dom mon dow   command
  0  */12     *   *   *     ./snake --eat-my-commits
  0  3        *   *   *     /usr/bin/second-wind
  0  9        *   *   1-5   echo "today I will finish it" > /dev/null
```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kartalc23/kartalc23/output/snake-dark.svg"/>
  <img alt="a snake eating a year of commits" src="https://raw.githubusercontent.com/kartalc23/kartalc23/output/snake.svg"/>
</picture>

```console
$ history | awk '{print $2}' | sort | uniq -c | sort -rn | head
```
```yaml
   4127  git
   3308  npm
   2214  cd
   1902  clear
    881  git   # (again, because the first one was staged wrong)
    674  rm    -rf node_modules
    673  npm   install
    412  :q!
     98  :wq
      3  man
```

```console
$ uptime
```
```yaml
 03:47:12  up 6 years, 214 days,  1 user,  load average: 2.31, 1.88, 0.94
```

```console
$ ping abdurrahman
```
```yaml
PING abdurrahman (github.com/kartalc23): 56 data bytes
64 bytes from issues:  seq=0  ttl=64  time=fast
64 bytes from pull-requests:  seq=1  ttl=64  time=faster
64 bytes from a-well-written-bug-report:  seq=2  ttl=64  time=0.1 ms

--- abdurrahman ping statistics ---
3 packets transmitted, 3 received, 0% packet loss

Open an issue. That is the whole protocol.
```

```console
$ exit
logout
Connection to kartal closed.

# kolay gelsin
```
