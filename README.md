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

## diga
digコマンドでANSWER SECTION結果をmarkdownの表で出力
```
% ./diga shigeki.tokyo 
|fqdn|type|record|
|----|----|------|
|shigeki.tokyo.|NS|01.dnsv.jp. |
|shigeki.tokyo.|NS|02.dnsv.jp. |
|shigeki.tokyo.|NS|03.dnsv.jp. |
|shigeki.tokyo.|NS|04.dnsv.jp. |
|shigeki.tokyo.|A|157.7.107.62 |
|shigeki.tokyo.|MX|10 mx01.lolipop.jp. |
|shigeki.tokyo.|TXT|"v=spf1 include:_spf.lolipop.jp. ~all" |
|shigeki.shop.|NS|01.dnsv.jp. |
|shigeki.shop.|NS|02.dnsv.jp. |
|shigeki.shop.|NS|03.dnsv.jp. |
|shigeki.shop.|NS|04.dnsv.jp. |
|shigeki.shop.|A|157.7.107.219 |
|shigeki.shop.|MX|10 mx01.lolipop.jp. |
|shigeki.shop.|TXT|"v=spf1 include:_spf.lolipop.jp ~all" |
```
