# Proxy List

این فایل توسط workflow شماره ۵ ساخته شده است.

> مقدار `ping_ms` زمان رفت‌وبرگشت یک درخواست HTTP/HTTPS از داخل GitHub Actions از مسیر همان proxy است؛ ICMP ping نیست.

## Fastest proxies

| Rank | PROXY_SERVER | PROXY_USERNAME | PROXY_PASSWORD | ping_ms | protocol | status | observed_ip | source |
|---:|---|---|---|---:|---|---:|---|---|
| 1 | `socks5://134.122.64.174:1080` | `` | `` | 807 | `socks5` | 200 | `134.122.64.174` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 2 | `socks4://185.214.108.46:40000` | `` | `` | 855 | `socks4` | 200 | `185.214.108.46` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks4.txt` |
| 3 | `http://185.221.237.57:8443` | `` | `` | 881 | `http` | 200 | `185.221.237.57` | `https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt` |
| 4 | `socks5://206.123.156.233:8246` | `` | `` | 907 | `socks5` | 200 | `142.132.202.85` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 5 | `socks4://58.235.170.51:5678` | `` | `` | 912 | `socks4` | 200 | `58.235.170.51` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks4.txt` |
| 6 | `socks5://206.123.156.226:4821` | `` | `` | 913 | `socks5` | 200 | `78.142.18.172` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks5.txt` |
| 7 | `socks5://206.123.156.224:6809` | `` | `` | 913 | `socks5` | 200 | `82.196.25.136` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 8 | `socks5://206.123.156.231:31704` | `` | `` | 956 | `socks5` | 200 | `157.180.91.87` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 9 | `socks5://206.123.156.233:7319` | `` | `` | 960 | `socks5` | 200 | `167.71.132.111` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 10 | `socks5://62.60.149.161:1080` | `` | `` | 968 | `socks5` | 200 | `62.60.149.161` | `https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/socks5.txt` |

## استفاده در workflow شماره ۴

در workflow `🌐 4-Browse the Web` مقدار `proxy_mode` را روی `fastest-from-file` بگذارید تا ردیف اول همین فایل استفاده شود. برای انتخاب ردیف دیگر، `proxy_mode=rank-from-file` و `proxy_list_rank` را برابر شماره ردیف جدول بگذارید.

فایل ماشینی متناظر: `proxy-list.json`
