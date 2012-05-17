# nginx vhost

A simple [giter8][g8] template for [nginx][nginx] vhost configuration files

## usage

Invoking

    g8 softprops/nginx-vhost \
      --name=awesome \
      --server_name=www.awesome.co \
      --proxy_pass=http://127.0.0.1:8080

with generate a new nginx vhost config file under a directory named awesome.

Doug Tangren 2012

[nginx]: http://wiki.nginx.org/Main
[g8]: https://github.com/n8han/giter8#readme
