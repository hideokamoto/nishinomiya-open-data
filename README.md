# 西宮市オープンデータAPI（仮・非公式）

西宮市が公開しているオープンデータを、JSON-LD形式の簡易API化したレポジトリです。

## 利用上の注意

- StaticなJSON-LDファイルを設置しているだけです
- 手動更新のため、西宮市がデータを更新した場合に反映までラグが発生する可能性があります

## データセット


### 西宮市緊急時給水拠点一覧データ

```
$ curl https://hideokamoto.github.io/nishinomiya-open-data/water.jsonld
```

[緊急時給水拠点(西宮市)](http://opendata.nishi.or.jp/opendata/ResultDetail.php?id=30)をJSON-LD形式に加工したものです。

#### 出典
- [緊急時給水拠点(西宮市)](http://opendata.nishi.or.jp/opendata/ResultDetail.php?id=30)（2018/01/17更新データをJSON-LD形式に加工）

### 西宮市指定避難場所・広域避難場所データ

```
$ curl https://hideokamoto.github.io/nishinomiya-open-data/shelte.jsonld
```


[避難所(西宮市)](http://opendata.nishi.or.jp/opendata/ResultDetail.php?id=2)をJSON-LD形式に加工したものです。

#### 出典
- [避難所(西宮市)](http://opendata.nishi.or.jp/opendata/ResultDetail.php?id=2)（2018/02/07更新データをJSON-LD形式に加工）

### 西宮市ゴミ分別情報データ

```
$ curl https://hideokamoto.github.io/nishinomiya-open-data/hello-gomi.jsonld
```

[西宮市のゴミ分別情報データ](http://opendata.nishi.or.jp/opendata/ResultDetail.php?id=26)をJSON-LD形式に加工したものです。

#### 出典
- [「ごみ収集日・分別情報」（西宮市）](http://opendata.nishi.or.jp/opendata/ResultDetail.php?id=26)（2018年3月5日更新データをJSON-LD形式に加工）
