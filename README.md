![Graylog:3.3.8](https://img.shields.io/static/v1?label=Graylog&message=3.3.8&color=green)

# Graylog GELF UDP Input 

Graylog >= 3.3.8 content-pack creates `Gelf UDP` input on port `12201`.

## Docker

Use as auto-install package when creating new graylog instances via docker. Mount file as
`/usr/share/graylog/data/contentpacks/graylog-default-gelf-udp.json` and make environment vars available:

```dotenv
GRAYLOG_CONTENT_PACKS_LOADER_ENABLED=true
GRAYLOG_CONTENT_PACKS_DIR=/usr/share/graylog/data/contentpacks
GRAYLOG_CONTENT_PACKS_AUTO_INSTALL=graylog-default-gelf-udp.json
```
