# OpenDaylight OpenStack 連携 コンフィグレーション(local.conf)

このリポジトリにはDevStackを用いてOpenDaylightとOpenStackを連携させるためのコンフィグレーションファイル(local.conf)を格納しています。

## リポジトリの構成
allinoneディレクトリは、OpenDaylightとOpenStackが同一ホストで構成する場合の設定ファイルが格納されています。

externalodlディレクトリは、OpenDaylightとOpenStackが異なるホストで構成される場合の設定ファイルが格納されています。

各ディレクトリ内のsingle-nodeとmulti-nodeディレクトリは、それぞれOpenStackがシングルノード構成であるか、またはコントローラノード（＋ネットワークノード）とコンピュートノードのマルチノード構成であるかを表しています。

## local.conf使用上の注意
この設定ファイルを使用するにはそれぞれのlocal.conf内のHOST_IPおよびSERVICE_HOSTをお使いの環境に合わせて変更して下さい。

##アップデート

- 2016/04/18 
  - ODLのバージョンをSNAPSHOTからSR4に修正。
