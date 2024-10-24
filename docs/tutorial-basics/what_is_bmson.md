---
sidebar_position: 1
---

# bmsonことはじめ

## 参考にさせていただいたサイト、ドキュメント
[えびです - .BMSONのザックリとした作り方](https://hackmd.io/@ebideath/BJT-vBVfs)  
[BmsONE 101 - The Basics](https://docs.google.com/document/d/178FvK-rVAcc-ZK5ls6gnMmaIphFmwF78JWIL8kRiGXA/edit#heading=h.vt3wr26clq0k)
## bmsonってなんぞや？
> wosderge氏が開発した新しいBMSフォーマットである。2015年8月13日にフォーマットが公開され、現在も改良が続いている。(BMSまとめWikiより)

らしいですが、技術資料の最新のコミットから**なんと9年**。
おそらくそんなんあったなぁ、みるけどよくわからないという人が大半ではないでしょうか？
## bmsonを使うメリット
* だばぁの心配がない。
* 読みこむファイル数が少ないため、速くなる（かも）
    * 使い回しの部分が微妙なためサイズは大きくなるかも
* **音切りが爆速**
* 定義数が実質無限
* ステムデータ（とMIDI）だけ用意すればいいのでDAWを介さず準備が楽
* 第三者が音切りを助けてあげられやすい
* JSONをもとに作られたフォーマットなのでJSONが扱える人はいじりやすい
## bmsonのデメリット
* 極限まで使い回すことを前提にしていないため、ファイルサイズは大きくなりがち。
    * 可能ではあるがそうなるとbmsonの意味がほぼ消滅
    * フレーズごとに分けるとよし。
    * ワンショット音源はエフェクトと要相談
* 新しく音ぎりの仕方覚えるのがめんどい。
    * 自分はこれがBMSデビューなので抵抗がなかった。
* bmsonを再生できるプレイヤーが限定される。
    * beatorajaはいいぞ
* ぶつ切り前提のため、音に違和感
    * フレーズの中で末端フェードを入れたり。
* 情報が少ない
    * なるべくこちらで更新していきます。
## 結論
**工夫次第でなんとかなる！**

**さあ始めよう(ｷﾘｯ)**


