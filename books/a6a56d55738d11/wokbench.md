---
title: "MySQL Workbenchの導入"
---

# MySQL Workbenchの導入

## MySQL Workbenchの利点

- SQLをGUIで書ける
- データモデリングしたER図をそのままスキーマに突っ込める
- SQLサーバーのパフォーマンスなどの管理ができる
- 他DBへのデータ移行が可能

## MySQL Workbenchのインストール

- MySQL installerを使う(installerは32bitだが、MySQLServerは64bitOSに対応している)
- インストールタイプは「Developer Default」を選択
  - Server OnlyだとMySQL Serverのみインストールされる
  - Client OnlyだとMySQL Clientのみインストールされる
  - FullだとMySQL ServerとMySQL Clientがインストールされる
  - CustomだとMySQL ServerとMySQL Clientの他に、MySQL WorkbenchやMySQL Utilitiesなどをインストールできる

### serverOnlyでInnoDbClusterをインストールしてみたいが気持ちを抑えてレプリケーションを抑えて、ほかの項目を読み終わってから挑むことにする

- MySQL Shell Routerなどを利用して後からでも組めるようになってそう

- [公式クラスター構築手順blogあった](https://dev.mysql.com/blog-archive/mysql-innodb-cluster-setting-up-a-real-world-cluster/)
- [MySQL Shell](https://dev.mysql.com/doc/mysql-shell/8.0/en/)
- [MySQL レプリケーションの新しそうな奴](https://dev.mysql.com/blog-archive/introducing-mysql-innodb-replicaset/)