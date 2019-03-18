# shellscript

## cghosts
hostsファイルをコマンドで書き換える (Mac)
```
Usage: cghosts [options] <ipAddr> <hostname>

  -v        Print the version and exit.
  -h        Print this help.

Options:
  -i        Information.
  -l        Registered Hosts.
  -a        Add Hosts.
  -r        Remove Hosts.
```

## digm
digコマンドでANSWER SECTION結果をmarkdownの表で出力
```
% ./digm kudaranai.info
|fqdn|type|record|
|----|----|------|
|kudaranai.info.|MX|10 aspmx.l.google.com. |
|kudaranai.info.|MX|20 alt2.aspmx.l.google.com. |
|kudaranai.info.|MX|30 aspmx2.googlemail.com. |
|kudaranai.info.|MX|20 alt1.aspmx.l.google.com. |
|kudaranai.info.|TXT|"v=spf1 include:_spf.google.com ~all" |
|kudaranai.info.|SOA|kudaranai.info. postmaster.kudaranai.info. 1465131791 3600 1800 604800 3600 |
|kudaranai.info.|NS|dns02.muumuu-domain.com. |
|kudaranai.info.|NS|dns01.muumuu-domain.com. |
|kudaranai.info.|A|157.7.107.219 |
|kudaranai.info.|MX|30 aspmx3.googlemail.com. |
```
