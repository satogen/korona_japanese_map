# コロナ感染者を日本地図にマッピングするプログラム

## 内容

CSV ファイルをもとに日本地図にコロナ感染者を色でマッピングします。

## 基本情報

- データ元
  - https://www.mhlw.go.jp/stf/newpage_09770.html

## データ取得方法

グーグルスプレッドシート上でこちらを実行し、CSV ファイルをダウンロード

```
=IMPORTHTML("url", "table", 3)
```

対象 URL がこちらの場合（https://www.mhlw.go.jp/stf/newpage_09747.html）の例

```
=IMPORTHTML("https://www.mhlw.go.jp/stf/newpage_09747.html", "table", 3)
```

## 参考情報

- IMPORTHTML 関数

  - https://roboma.io/blog/marketing/importhtml-function-of-google-spreadsheet/

- 厚生労働省コロナ感染者の情報
- https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/0000121431_00086.html
