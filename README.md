# モザイク除去から学ぶ　最先端のディープラーニング
2020年の技術書典8で頒布する予定だった（コロナウイルスにより中止）『モザイク除去から学ぶ　最先端のディープラーニング』の質問用のリポジトリです

![](https://github.com/koshian2/MosaicDeeplearningBook/blob/master/images/title.png)

## このリポジトリについて
issueに投げていただいた質問を、著者のこしあんさん（@koshian2）が気まぐれで回答します。他の方が回答していていただいても構いません。本に関係ないことはスルーする場合があります。日本語で書ける方は日本語で書いてください（英語だと読むのが面倒くさいので）。

## 本について
以下、ブログ記事についてのまとめページになります。

**[感想まとめはこちら](https://github.com/koshian2/MosaicDeeplearningBook/blob/master/%E6%84%9F%E6%83%B3.md)**

本の詳細：[https://qiita.com/koshian2/items/aefbe4b26a7a235b5a5e](https://qiita.com/koshian2/items/aefbe4b26a7a235b5a5e)

### 目次
![](https://github.com/koshian2/MosaicDeeplearningBook/blob/master/images/index1.png)
![](https://github.com/koshian2/MosaicDeeplearningBook/blob/master/images/index2.png)
![](https://github.com/koshian2/MosaicDeeplearningBook/blob/master/images/index3.png)

## 訂正
* p.33 「ディープラーニング入門　Q9解答」
  + 誤：```model.fit(X_train, y_train, validation_data=(X_train, y_train), epochs=10)```
  + 正：```model.fit(X_train, y_train, validation_data=(X_test, y_test), epochs=10)```
* p.34 「画像処理の畳み込みから畳み込みニューラルネットワークへ　Q13解答」
  + 誤：```outputs = tf.nn.conv2d(float_img, contour_kernel, 1, padding="SAME")outputs += 1.0```
  + 正：```outputs = tf.nn.conv2d(float_img, contour_kernel, 1, padding="SAME")```(改行)```outputs += 1.0```
* p.38 typo 誤：「画像の縮小や縮小において」　正：「画像の拡大や縮小において」
* p.40　typo 誤：「したｇって」　正：「したがって」

## 通販会場
### Booth
Boothでは物理版（紙の本）＋電子版、電子版の2種類を用意しております。物理版の配送に時間がかかることがありますが、電子版はおまけファイルよりすぐ読むことができます。

<a href="https://koshian2.booth.pm/items/1835219"><img src="https://asset.booth.pm/static-images/banner/468x60_02.png"></a>

**[https://koshian2.booth.pm/items/1835219](https://koshian2.booth.pm/items/1835219)**

* 物理版＋電子版：2500円、送料別途400円～
* 電子版：1800円

Boothは発送に1週間程度かかるので、物理版をお急ぎの方・正式な領収書が必要な方はとら、メロンなどの委託書店をご利用ください。

### メロンブックス
2020年5月委託開始。物理版に電子版のDLコードが付属している（表紙の裏側に貼ってあります）ので、メール送付は不要です。

**[https://www.melonbooks.co.jp/detail/detail.php?product_id=670234](https://www.melonbooks.co.jp/detail/detail.php?product_id=670234)**

万が一、DLコードに不備があった（ダウンロードできないなど）場合は、DLコードを明記の上奥付にありますメールアドレスまでご連絡ください。ただし、中古購入の場合は一切保証できませんのでご承知おきください。

### とらのあな
物理版のみの取り扱いとなります。とらのあな不定期で一定金額以上購入で送料無料キャンペーンを行っています。詳しくは公式サイトをご確認ください。

委託書店での頒価は、メロン・とらともに3000円＋税です。各種店舗のクーポンをぜひご利用ください。

### 電子版のみ（3箇所）
Booth、Fantia、Noteの3つで展開しております。プラットフォーム手数料の関係で価格が異なりますが、決済方法が違うのでお好きなのをご利用ください。決済方法につきましては各プラットフォーム公式サイトを参照してください。

* Booth : **[https://koshian2.booth.pm/items/1835219](https://koshian2.booth.pm/items/1835219)**
* Note : **[https://note.com/koshian2/n/n8ebe5345306c](https://note.com/koshian2/n/n8ebe5345306c)**
* DLsite : **[https://www.dlsite.com/home/work/=/product_id/RJ314824.html](https://www.dlsite.com/home/work/=/product_id/RJ314824.html)**
* 技術書典OM：**[https://techbookfest.org/product/5740557385072640?productVariantID=5682774170140672](https://techbookfest.org/product/5740557385072640?productVariantID=5682774170140672)**

電子版のみ価格

* Booth：1800円
* Note：1850円
* DLsite：2090円
* 技術書典OM：1800円

## 在庫・配送状況
2021/1/20時点

* Booth：在庫あり
* とらのあな：在庫あり
* メロンブックス：在庫わずか

## 領収書について
宛名変更可能な領収書は[とらのあな](https://customer.toranoana.jp/faq_detail.html?id=9999469)をご利用ください。[メロンブックスでも領収書](https://www.melonbooks.co.jp/help/tpl.php?cid=165)は発行できます。Boothでの領収書発行の個別対応は行っていません。

委託店舗の領収書についてご不明な点があれば、恐れ入りますが各店舗に問い合わせていただきますようお願いいたします。

## 過去のおしらせ
* 2020/4/30 [おもしろ同人誌バザール（おもバザオンライン）に出展します](https://note.com/koshian2/n/n02ae8d653728)
* 2020/4/9 [技術書典8の新刊を通販だけで頒布した人の赤裸々な収支報告](https://note.com/koshian2/n/nf38e836988a9)
* 2020/3/26 [出版社経由の本の商業化を断りました](https://note.com/koshian2/n/n15c50e5173c3)
* 2020/3/19 [「#技術書典　応援祭」参加したくても参加できなかった人の話](https://note.com/koshian2/n/n0581d480e67a)
* 2020/3/19 [Booth倉庫の入荷・発送遅延につきまして](https://blog.shikoan.com/techbook08-news05/)
* 2020/3/7 [ご報告](https://blog.shikoan.com/techbook08-news04/)
* 2020/3/3 **とらの還元キャンペーンについて記載**　[新刊のご購入にはとらのあなが便利です](https://blog.shikoan.com/techbook08-news03/)
* 2020/2/29 [技術書典8の新刊の書籍版＋電子版の注文受付を開始しました](https://blog.shikoan.com/techbook08-news02-2/)
* 2020/2/29 **とらの電子版プレゼントについて記載** [新刊『モザイク除去から学ぶ　最先端のディープラーニング』のとらのあなでの販売が始まりました](https://note.com/koshian2/n/nfe3961acb389)
* 2020/2/28 [新刊『モザイク除去から学ぶ　最先端のディープラーニング』の注文受付を開始しました](https://note.com/koshian2/n/n4bf9bdd19699)
* 2020/2/22 [技術書典8の当日開催が中止になっても新刊を出す7つの理由](https://blog.shikoan.com/techbook08-news02/)
* 2020/2/15 [新型肺炎に対する2/15時点での想定について](https://blog.shikoan.com/techbook08-sp/)
* 2020/2/14 [技術書典8で新刊を委託します！](https://blog.shikoan.com/techbook08-news1/)
* 2019/12/16 [技術書典8落選しました](https://note.com/koshian2/n/n6b69960a7d67)

## 演習問題（無料公開分のみ）
無料公開分の演習問題です。ご自由にチャレンジください。無料公開分以外のURLの共有などはご遠慮ください。解答は試し読みPDFにあります。

### 1章　機械学習・ディープラーニング・畳み込みニューラルネットワーク

* Colaboratory・Pythonチュートリアル（初心者向け） [https://colab.research.google.com/drive/1wenkuZYMdOnTo-cis0qmvN4MgfTvTxm6](https://colab.research.google.com/drive/1wenkuZYMdOnTo-cis0qmvN4MgfTvTxm6)
* 演習問題１：ディープラーニング入門 [https://colab.research.google.com/drive/1lFEAvFrXUuRY_yeXC7AK2LlC3pPZ2tYv](https://colab.research.google.com/drive/1lFEAvFrXUuRY_yeXC7AK2LlC3pPZ2tYv)
* 演習問題２：画像処理の畳み込みから畳み込みニューラルネットワークへ [https://colab.research.google.com/drive/1vq5fvJvQlRq7ehsi8UJV8RKpYE4TiTf3](https://colab.research.google.com/drive/1vq5fvJvQlRq7ehsi8UJV8RKpYE4TiTf3)
* 演習問題３：畳み込みニューラルネットワーク [https://colab.research.google.com/drive/1QImzsStP7Ba3Yfb6GAYZaEhkmByXEg06](https://colab.research.google.com/drive/1QImzsStP7Ba3Yfb6GAYZaEhkmByXEg06)
* 演習問題（オプション）：Colab TPUによるCNNの訓練 [https://colab.research.google.com/drive/1D9jqqY-zEm7Wzns_7OAr73UATnsVK-T4](https://colab.research.google.com/drive/1D9jqqY-zEm7Wzns_7OAr73UATnsVK-T4)

