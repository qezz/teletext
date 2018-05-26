# Teletext

A telegram bot to transform text

# Available commands:

 - `/square`
 - `/star`
 - `/qstar`

# Running

```sh
$ git clone https://github.com/rossnomann/teletext && cd teletext
$ cargo build --release
$ # or download from releases page on github
$ cat <<EOF > .env
TELETEXT_TOKEN=your-bot-token
EOF
$ /target/release/teletext
```

You can add `ALL_PROXY='socks5h://user:pass@host:port'`
to `.env` file in order to use a socks5 proxy.

# Changelog

### 0.1.0 (26.05.2018)

- First release.

## LICENSE

The MIT License (MIT)