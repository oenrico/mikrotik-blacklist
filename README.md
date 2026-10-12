# MikroTik Blacklist

Public IP blacklist feed for MikroTik routers.

## Feed

`blacklist.txt` contains one IPv4 address or CIDR network per line.

Raw URL:

`https://raw.githubusercontent.com/oenrico/mikrotik-blacklist/main/blacklist.txt`

Lines beginning with `#` are comments and should be ignored by import scripts.

The list is intended to be generated automatically from security systems such as Fail2ban and synchronized periodically by MikroTik routers.
