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

### example result
```bash
$ ./ipinfo 8.8.8.8

IP        : 8.8.8.8
HOSTNAME  : google-public-dns-a.google.com
CITY      : Mountain View
REGION    : California
COUNTRY   : US
LOC       : 37.3860,-122.0838
ORG       : AS15169 Google Inc.
POSTAL    : 94035
```

*service provided by [ipinfo.io](http://ipinfo.io/)*
