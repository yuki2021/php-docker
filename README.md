# php-docker
自分が使う用のPHPやらMySQLが入ったDocker

https://github.com/yuki2021/mysql-docker

上記と合わせて使う用。

```
$ sudo docker network create sample-network
```

コンテナ間ネットワークを繋ぐことで、php-dockerの方からmysql-dockerよりデータ取得可能。