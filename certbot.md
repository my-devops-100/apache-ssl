```
root@iZbp18rrc2e8dbelayrwl7Z:~# certbot --nginx --agree-tos -d 'www.lv993.com' -m 'sikuan.gu@gmail.com'
Saving debug log to /var/log/letsencrypt/letsencrypt.log

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
Would you be willing, once your first certificate is successfully issued, to
share your email address with the Electronic Frontier Foundation, a founding
partner of the Let's Encrypt project and the non-profit organization that
develops Certbot? We'd like to send you email about our work encrypting the web,
EFF news, campaigns, and ways to support digital freedom.
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
(Y)es/(N)o: n
Account registered.
Requesting a certificate for www.lv993.com

Successfully received certificate.
Certificate is saved at: /etc/letsencrypt/live/www.lv993.com/fullchain.pem
Key is saved at:         /etc/letsencrypt/live/www.lv993.com/privkey.pem
This certificate expires on 2024-11-28.
These files will be updated when the certificate renews.
Certbot has set up a scheduled task to automatically renew this certificate in the background.

Deploying certificate
Successfully deployed certificate for www.lv993.com to /etc/nginx/sites-enabled/default
Congratulations! You have successfully enabled HTTPS on https://www.lv993.com

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
If you like Certbot, please consider supporting our work by:
 * Donating to ISRG / Let's Encrypt:   https://letsencrypt.org/donate
 * Donating to EFF:                    https://eff.org/donate-le
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

```