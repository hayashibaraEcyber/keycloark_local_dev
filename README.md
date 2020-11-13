# keycloark ローカル確認環境

+ Keycloak のローカル検証環境
+ Keycloak / MariaDB / OpenLDAP 連携

## ローカルにインストール

+ [Vagrant](https://www.vagrantup.com/downloads) ver 2.2.13
+ [Virtual Box](https://www.virtualbox.org/wiki/Downloads) ver 6.1.16

## Virtualbox起動

~~~cmd
vagrant plugin install ansible vbguest
vagrant plugin update
vagrant up --provision
~~~

## エラーになった時

~~~sh
vagrant vbguest --do install
vagrant reload --provision
~~~
