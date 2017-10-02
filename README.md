# serverpilot-apache-confs
Custom Apache .conf files for serverpilot (block bad bots, prevent PHP executions on missing files requests and set HTTPS 'on' for HTTPS forwarded requests (compatibilize WP and other apps with CF Flexible SSL)

## Installation

```
# run as root
git clone https://github.com/renatofrota/serverpilot-apache-confs.git
mv serverpilot-apache-confs/*.conf /etc/apache-sp/conf.d/
rm -rf serverpilot-apache-confs
```
