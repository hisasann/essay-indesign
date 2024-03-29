# ミックスナッツは高いほうがいい

## 本のサイズ

- 四六判 128mm x 188mm
  - やっぱりやめて **B6 サイズにした 128mm x 182mm**
  - やめた理由は、僕が好きな日記本たちが B6 だったため
- 本文文字サイズ 13Q
- ノンブル文字サイズ 10Q

## フォント

### Photoshop - 表紙たちで使ったフォント

`解星 春の海 - Kaisei HarunoUmi`

https://free-fonts.jp/kaiseiharunoumi/

https://fonts.google.com/specimen/Kaisei+HarunoUmi

### InDesign - 本文で使ったフォントたち

`游明朝体`

## InDesign書き出し

### 本文

![honbunの書き出し.png](assets%2Fhonbun%E3%81%AE%E6%9B%B8%E3%81%8D%E5%87%BA%E3%81%97.png)

PDF 書き出しプリセット： `[高品質印刷](変更)`

書き出し形式は `ページ` を選択する。

これにより、左右のページが1ページになる。

### 表紙

![hyoshiの書き出し.png](assets%2Fhyoshi%E3%81%AE%E6%9B%B8%E3%81%8D%E5%87%BA%E3%81%97.png)

PDF 書き出しプリセット： `[高品質印刷](変更)`

書き出し形式は `見開き` を選択する。

これにより、表紙の3ページ全体が PDF の1ページになる。


## InDesignでカバーを作る方法

https://sksksketch.net/tips/advc2022-techbook-howto.html

新規ドキュメントを作る時にマージンを 0mm にするのが大事。

これをしないと、3枚ページを横並びにして間を背表紙として使う場合に、マージンがあるとそれ以下に幅を小さくできないので、ここはハマりポイントだ。

ページの `ドキュメントページの移動を許可` のチェックを外す。

これをしないと、ページを横並びにできない。

## 文字数・ページ数

```shell
$ wc -m *.md
```

## 背表紙のサイズ

200ページで大体1cm。

300ページで大体1.5cm。

つまり100ページで5mmぐらいのようだ。

今回のオーダーの上質紙70K（書籍用紙72.5K）の場合 → 本文ページ数×0.05mm＝本文厚み

15.6mm

128+128+15.6=271.6mm

271.6mm が表紙・背表紙・裏表紙全体の幅になる。

## 印刷会社

### ブックホン

https://www.book-hon.com/

四六判のパターン。

- 印刷方法:オンデマンド印刷
- 納期コース:超ゆったりコース(10営業日)
- 部数:50
- サイズ:カスタム 128 mm（横） × 188 mm（縦）
- 製本仕様:無線綴じ
- 綴じ:右綴じ
- 用紙:コート135K
- 表紙用紙の色:白
- 用紙:上質70K
- 本文印刷:両面
- 本文ページ数:270 ページ
- 本文の印刷方法:モノクロ
- 入稿データ形式:PDF形式
- 本のタイトル:生活の日記
- サンプル印刷:あり
- 扉:なし
- 片袖折り(Z折り):なし
- PP加工:なし
- 見返し加工:なし
- 穴(２穴)あけ加工:なし

- オンデマンド印刷 46,897 円（税込） 一冊あたり937.9円
- オフセット印刷 93,387 円（税込） 一冊あたり1867.7円

これだと1000円で売ると、60円の利益か。

結構お値段が高い。

### ちょ古っ都製本工房

https://www.chokotto.jp/genkounyuukou.html

この印刷会社を使っている日記本が僕が持っている中ではダントツで多かった。
そして見積もったり、 PDF のアップロード機能含め、使いやすかった。
PDF をアップロードするとサイズが少し合わなかった。

- くるみ製本

実際のオーダーしたのは以下の通りだ。

![order-chokotto.png](assets%2Forder-chokotto.png)

- 30650 * 1.33（卸値67%を加味） = 40,764
- 50-(50*0.40) = 30冊
  - 返品率は約40％を想定
- 40,764 / 30 = 1,358円
  - つまりこの値段で売らないと儲けが出ないかもしれないという話
  - さらには30冊は売らないと赤字になってしまう想定
- 一冊1400円か〜
 
## 参考記事

- [InDesignで文庫サイズ同人誌を作ったメモ｜hibiki](https://note.com/_hibiki_/n/n4df4205ddf59)
- [InDesignで小説同人誌（文庫）を簡単に作る～第一回 - レン高原で待ってる](https://fujasin.hatenablog.com/entry/2018/10/05/101923)
- [InDesignだけの世界 - YouTube](https://www.youtube.com/@indesign1411/)

## 🍟 Author

- [github/hisasann](https://github.com/hisasann)
- [twitter/hisasann](https://twitter.com/hisasann)

## 🥫 License

MIT © [hisasann (Yoshiyuki Hisamatsu)](https://github.com/hisasann)