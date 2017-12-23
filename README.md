# zabbix_template_nginx

nginx Template for Zabbix ~> 3.4.

Necessary "Dependent Item". Put userparameter_nginx.conf in Include-UserParameter's Directory.

Necessary nginx_stub_status.

- ZABBIX 3.4用 nginxのテンプレートです。
- UserParameterのワインライナーでstub_statusをJSON化して、依存アイテムで各値を入れてます。
- Nginxのstub statusの取り方は各自適当に。conf置いておきます。
- webpage.regexpの仕様がよくわからんので、わかったらいれかえるかも。
- FreeBSD11/CentOS7.1以上で動きます。

このテンプレートはMIT Licenseです。
