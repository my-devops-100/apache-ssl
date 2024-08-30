# Apache中使用SSL - 小布老师

---

```
/opt/openssl/bin/openssl: /lib/x86_64-linux-gnu/libcrypto.so.3: version `OPENSSL_3.0.9' not found (required by /opt/openssl/bin/openssl)
```

> <https://github.com/openssl/openssl/issues/19801>

```
LD_LIBRARY_PATH=LD_LIBRARY_PATH=/opt/openssl/lib64
```

---

```
configure: error: APR not found.  Please read the documentation.
```

> <https://stackoverflow.com/questions/13967114/configure-error-apr-not-found-please-read-the-documentation>

```
sudo apt-get install libapr1-dev libaprutil1-dev
```

---
```
configure: error: pcre(2)-config for libpcre not found. PCRE is required and available from http://pcre.org/
```

> <https://stackoverflow.com/questions/10663180/apache-installation-libpcre-error>

```
sudo apt-get install libpcre2-dev
```

---

```
configure: WARNING: OpenSSL version is too old
```

## Ref

* <http://www.boobooke.com/m2/index.html>
* [How To Create a Self-Signed SSL Certificate for Apache in Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-apache-in-ubuntu-22-04)
* [https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-nginx-in-ubuntu](https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-nginx-in-ubuntu)
* [How To Secure Apache with Let's Encrypt on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-secure-apache-with-let-s-encrypt-on-ubuntu)