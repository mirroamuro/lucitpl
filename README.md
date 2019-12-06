# OpenWrt luci feed

×·¼ÓÒ»Ì×Ä£°å Refresh Theme

## Usage

This feed is enabled by default. Your feeds.conf.default (or feeds.conf) should contain a line like:
```
src-git luci https://github.com/mirroamuro/lucitpl.git
```

To install all its package definitions, run:
```
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```