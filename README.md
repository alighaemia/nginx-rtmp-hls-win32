# nginx-rtmp-hls-win32
Nginx with RTMP+HLS module for Windows.
================
forked from illuspas/nginx-rtmp-win32

* Nginx: 1.14.1  
* Nginx-Rtmp-Module: 1.2.1  
* openssl-1.0.2p
* pcre-8.42
* zlib-1.2.11

# Configure arguments
```
nginx version: nginx/1.14.1
built by cl 18.00.40629 for x86
built with OpenSSL 1.0.2p  14 Aug 2018
TLS SNI support enabled
configure arguments: --with-cc=cl --builddir=objs --with-debug --prefix= --conf-
path=conf/nginx.conf --pid-path=logs/nginx.pid --http-log-path=logs/access.log -
-error-log-path=logs/error.log --sbin-path=nginx.exe --http-client-body-temp-pat
h=temp/client_body_temp --http-proxy-temp-path=temp/proxy_temp --http-fastcgi-te
mp-path=temp/fastcgi_temp --http-scgi-temp-path=temp/scgi_temp --http-uwsgi-temp
-path=temp/uwsgi_temp --with-cc-opt=-DFD_SETSIZE=1024 --with-pcre=objs/lib/pcre-
8.42 --with-zlib=objs/lib/zlib-1.2.11 --with-select_module --with-http_v2_module
 --with-http_realip_module --with-http_addition_module --with-http_sub_module --
with-http_dav_module --with-http_stub_status_module --with-http_flv_module --wit
h-http_mp4_module --with-http_gunzip_module --with-http_gzip_static_module --wit
h-http_auth_request_module --with-http_random_index_module --with-http_secure_li
nk_module --with-http_slice_module --with-mail --with-stream --with-openssl=objs
/lib/openssl-1.0.2p --with-openssl-opt=no-asm --with-http_ssl_module --with-mail
_ssl_module --with-stream_ssl_module --add-module=objs/lib/nginx-rtmp-module/
```

# Instructions
Double click nginx.exe

# Description

* conf/nginx.conf Configuration file instance

* RTMP listens to port 1935, enabling live and hls two applications

* HTTP listening port 8080,

* localhost:8080/stat View stream status

# Attention
exec is not supported
