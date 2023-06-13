# 日本の住所に関する符号

このリポジトリは、日本の住所に関する符号の一覧を整理し、CSVファイル形式で公開するものです。

| コード           | 参照元  | 更新 |
| ---------------- | ------- | ---- |
| 都道府県コード   | https://nlftp.mlit.go.jp/ksj/gml/codelist/PrefCd.html | -- |
| 市区町村コード | https://www.soumu.go.jp/denshijiti/code.html | 令和5年4月1日更新版 |


## 都道府県コード

各都道府県に対応するコードを列挙したCSVファイルが含まれています。

ファイル名： `prefcode.csv`

CSVファイルの形式は次のとおりです：

```
都道府県コード,都道府県名
01,北海道
02,青森県
03,岩手県
...
47,沖縄県
```

## 市区町村コード (citycode.csv)

市区町村に対応するコードを列挙したCSVファイルが含まれています。

ファイル名： `citycode.csv` および `citycode_seireishi.csv`

CSVファイルの形式は次のとおりです：

```
団体コード,"都道府県名（漢字）","市区町村名（漢字）","都道府県名（カナ）","市区町村名（カナ）"
010006,北海道,,ホッカイドウ,
011002,北海道,札幌市,ホッカイドウ,サッポロシ
012025,北海道,函館市,ホッカイドウ,ハコダテシ
012033,北海道,小樽市,ホッカイドウ,オタルシ
012041,北海道,旭川市,ホッカイドウ,アサヒカワシ
...
```

## 使い方

1. リポジトリをクローンまたはダウンロードします。

```bash
git clone https://github.com/archlabjp/jpaddress-codes.git
```

2. 必要に応じて、CSVファイルを開き、データを利用します。

## 貢献

データの誤りや改善のための提案など、フィードバックや貢献をお待ちしております。issueやpull requestを通じて貢献をお願いします。

## ライセンス

このデータは[CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)で公開されており、全世界でどのようにでも自由に使うことができます。

## ディスクレーマー

このリポジトリのデータは、最善を尽くして正確さを確保していますが、それが保証されるものではありません。データを使用する際は自己責任でお願いします。

## 著者

Youworks Corp.