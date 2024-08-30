# 第7课: 在Apache中使用SSL系列视频-7

|本期版本|上期版本
|:---:|:---:
`Fri Aug 30 12:28:08 CST 2024` | -

```
./configure --help|grep ssl
./configure --prefix=/opt/www \
    --enable-ssl \
    --with-ssl=/opt/openssl
```

```
httpd -l
```


---

> `mod_so`: 动态加载模块

```
apt-get install apach2

# /etc/apache2/mods-available/ssl.load
a2enmod ssl
```

---

```
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/ssl/private/apache-selfsigned.key -out /etc/ssl/certs/apache-selfsigned.crt

```

* `-x509`: 证书格式
* `-days 365`: 有效期
* `-keyout`: 私钥文件
* `-out`: 数字证书(包含公钥文件)
* `

---

```
openssl req -new -x509 -days 30 -keyout server.key -out server.crt -subj '/CN=Test-Only Certificate'
```