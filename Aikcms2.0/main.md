# Aikcms

---

* Project official：http://www.aikcms.com
* project address:   http://www.aikcms.com

---

## del SQLINJECT

>URL: http://127.0.0.1/admin/page/union/ad_list.php?del=5
![Alt text](/Aikcms2.0/img/2.png)
>Debug:Almost all code involving the delete function has security issues eg:/admincore/nav.php
![Alt text](/Aikcms2.0/img/8.png)

* POST:
```
GET /admin/page/system/nav.php?del=4 HTTP/1.1
Host: 127.0.0.1
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Referer: http://127.0.0.1/admin/page/system/nav.php
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: adminname=admin; MEIQIA_EXTRA_TRACK_ID=1F7WZdk3rwHIzKqUfkrNaZ9t1EE; _ga=GA1.1.1842664860.1547715044; UM_distinctid=169c55686280-0636c606d502d3-36664c08-1fa400-169c556862b2e4; CNZZDATA1256162028=1606185978-1553793969-%7C1553793969; CNZZDATA1707573=cnzz_eid%3D987595238-1554794879-http%253A%252F%252F127.0.0.1%252F%26ntime%3D1554913098; __atuvc=2%7C17; PHPSESSID=vg87i25i1bmauptoprvi3m1l43
Connection: close
```
>verification:
![Alt text](/Aikcms2.0/img/7.png)

## File upload vulnerability

>URL:Upload function page
![Alt text](/Aikcms2.0/img/1.png)
>debug:Almost all code involving the update function has security issues eg:/admincore/nav.php
![Alt text](/Aikcms2.0/img/4.png)

* POST
![Alt text](/Aikcms2.0/img/5.png)

>verification:
![Alt text](/Aikcms2.0/img/6.png)
