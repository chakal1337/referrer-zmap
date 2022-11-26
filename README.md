```bash
sudo apt install zmap
```

```bash
go install github.com/zmap/zgrab@latest
```

```bash
echo -e "GET / HTTP/1.1\r\nHost: %s\r\nUser-Agent: Mozilla/5.0\r\nReferer: https://your.site/\r\nConnection: close\r\n\r\n" > data
```

```bash
sudo zmap -p 80 | zgrab -data data
```
