# ipinfo-cli
CLI for ipinfo.io

*requires php.*

## usage

### getting own ip
```bash
$ ./ipinfo
```

### ip info
```bash
$ ./ipinfo 8.8.8.8
```

### ip info (IPv6)
```bash
$ ./ipinfo 2601:9:7680:363:75df:f491:6f85:352f
```

### ip info by domain
```bash
$ ./ipinfo github.com
```

### example result
```bash
$ ./ipinfo github.com
IP       = 192.30.252.129
HOSTNAME = github.com
CITY     = San Francisco
REGION   = California
COUNTRY  = US
LOC      = 37.7697,-122.3933
ORG      = AS36459 GitHub, Inc.
POSTAL   = 94107
```

*service provided by [ipinfo.io](http://ipinfo.io/)*
