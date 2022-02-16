# ServeZero - マルチドメインホスティングシステム

複数のWebアプリケーションをマルチドメインで運用できるホスティングシステムです。システムは１台のサーバ上で稼働します。

## コンセプト

- 複数のドメインの多種のWebアプリケーションをGUIのみで運用管理できるシステム
- サーバリソースを最大限に生かした作り(→運用費用の低減)
- サーバコンテナ技術で安定したWebアプリケーションの運用と技術の変化への機敏な対応(Dockerコンテナを使用)

## 運用できるWebアプリケーション

LEMP(Nginx + MariaDb + PHP)型のWebアプリケーションが運用できます。  

### 現在インストール可能なWebアプリケーション

- WordPress
- Joomla!

## 対象OS
- CentOS Linux v8
- Rocky Linux v8
- Alma Linux v8

## ライセンス

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

## インストール
新規にOSをインストールしたサーバに`root`でログインし、以下の１行のコマンドをそのままコピーして実行します。  
インストール完了後、サーバを再起動します。

### 実行コマンド
```
curl https://raw.githubusercontent.com/ServeZero/servezero/master/script/build_env.sh | bash
```

## クイックスタート

Webブラウザで管理画面にアクセスします。

```
http://[サーバのIP]:8080
```

初期アカウント`admin@example.com`、パスワード`admin`でサインインします。

## 関連レポジトリ

- システム管理用Webアプリケーション(https://github.com/ServeZero/servezero-app )
