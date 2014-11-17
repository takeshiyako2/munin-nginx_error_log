This is munin plugin for count of Nginx error.log.


# How to setup

```
# cd /usr/share/munin/plugins/
# wget --no-check-certificate https://raw.githubusercontent.com/takeshiyako2/munin-nginx_error_log/master/nginx_error_log
# chmod +x nginx_error_log
# ln -s /usr/share/munin/plugins/nginx_error_log /etc/munin/plugins/nginx_error_log
# munin-run nginx_error_log
nginx_error_log.value 12
# service munin-node restart
```


# AUTHOR

Contributed by Takeshi Yako
https://github.com/takeshiyako2

# LICENSE

MIT

