### nginx/1.10.x

TLS SNI support enabled

--prefix=/etc/nginx 

--sbin-path=/usr/sbin/nginx 

--conf-path=/etc/nginx/nginx.conf 

--error-log-path=/var/log/nginx/error.log 

--http-log-path=/var/log/nginx/access.log 

--pid-path=/var/run/nginx.pid 

--lock-path=/var/run/nginx.lock 

--http-client-body-temp-path=/var/cache/nginx/client_temp 

--http-proxy-temp-path=/var/cache/nginx/proxy_temp 

--http-fastcgi-temp-path=/var/cache/nginx/fastcgi_temp 

--http-uwsgi-temp-path=/var/cache/nginx/uwsgi_temp 

--http-scgi-temp-path=/var/cache/nginx/scgi_temp 

--user=nginx 

--group=nginx 

--with-http_ssl_module 

[--with-http_realip_module](http://nginx.org/en/docs/http/ngx_http_realip_module.html)

--with-http_addition_module 

[--with-http_sub_module](http://nginx.org/en/docs/http/ngx_http_sub_module.html)

--with-http_dav_module 

--with-http_flv_module 

--with-http_mp4_module 

--with-http_gunzip_module 

--with-http_gzip_static_module 

--with-http_random_index_module 

--with-http_secure_link_module 

[--with-http_stub_status_module](http://nginx.org/en/docs/http/ngx_http_stub_status_module.html)

--with-http_auth_request_module 

--with-threads

--with-stream

--with-stream_ssl_module

--with-http_slice_module

--with-mail 

--with-mail_ssl_module 

--with-file-aio 

--with-http_v2_module

--with-ipv6 

### dynamic modules:

nginx-module-geoip

nginx-module-image-filter

nginx-module-njs

nginx-module-perl

nginx-module-xslt