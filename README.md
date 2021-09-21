# ansible-apache2

An Ansible role for installing the Apache web server.

## Role Variables

- `apache_version` - Apache version
- `apache_delete_default_site` - Whether or not to delete the default Apache site (default: `False`)
- `apache_port` - Default port for Apache to listen on (default: `80`)
- `apache_ssl_port` - Default port for Apache to listen for SSL on (default: `443`)

## Reference

This ansible role is taken mostly out of [azavea.apache2](https://github.com/azavea/ansible-apache2.git) from Azavea Inc., but I stripped it down for brevity.