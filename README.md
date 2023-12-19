# NR-make
このソフトウェアは，新たにNginxベースのリバースプロキシを構築する状況を想定しています．ユーザはリバースプロキシを構築したいVMのホームディレクトリに"NR-make.sh"を配置してください．

## make_nginx_proxy.sh
構築処理を行うスクリプトファイルの古いバージョンです．
プロキシ対象のステータスコード確認の処理が含まれていません．
Webページ以外（データベース等）のserviceにもプロキシ設定されてしまうため，基本使いません．

## NR-make.sh
実際に構築処理を行うスクリプトファイルです．
VMに配置後，以下のコマンドで実行してください．

```$ bash NR-make.sh```
