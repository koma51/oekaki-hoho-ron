---
layout: post
permalink: :title/
title: パース理論の予備知識
description: パースの基礎知識と歴史について簡単に触れて、これから理論を学ぶ準備をします。
thumb: /assets/img/2013-03-14/00.png

categories:
- 透視図法

tags:
- 2点透視図法
- 3点透視図法

---

- ### 目次
- [パース法の基礎技法](#パース法の基礎技法)
- [パース法の歴史](#パース法の歴史)
- [パース法を学ぶ意義](#パース法を学ぶ意義)

パース法は、絵心の必要ないお絵描きテクニックです。誰でも一点透視図法や二点透視図法で立体を描いたことがあるでしょう。絵の上手い下手関は係なく「知っているか」どうかで話ができるのがパース法です。では、既に理論が確立しているのに何故、勉強すれば誰でも習得できるはずのパース法が苦手な人が多いのでしょうか。

それはやはり、明確な使用目的が分からないため、何が重要で、どこからどこまで押さえておけばいいのか分からないから嫌になるのでしょう。目的の無い理論ほど無意味なものはありません。ですから今回は、ありとあらゆるパース法を使用する「場面」を想定し、そのとき目的から逆算してパース法の基礎理論の「使い方」を考えていきます。

取りあえずはパース法というものについて正しく向き合うために、軽く予備知識を蓄えようと思います。やはり学ぼうとしている事柄の概要を把握しておくことは大切だと思います。特に歴史のある学問は、どのような発展を遂げてきたのか、関連事項は何か、正式な定義は何かなどという項目は押さえておく努力はしないといけません。その上で技術的に習得するにはどうするかを考えていこうと思います。

## パース法の基礎技法

手始めにパース法の基本的な技法のことでも書いておきましょうか。パースとはパースペクティブの略で、遠近法や透視図のこと、つまり目に映る像を平面に正確に写すための技法です。よく知られる技法には一点透視図法、二点透視図法、三点透視図法がありますが、四点透視図法はありません。現実世界の空間は三次元で構成されているから当然ですね。もし四次元の絵が描けたらそれ下さい。話を戻します。先ほど列挙した透視図法は、線で幾何学的に遠近感を描く技法なので線遠近法というらしいです。一方、幾何学的でない空気遠近法というものもあります。これは大気中の水蒸気や塵などによって光が拡散して色が薄くなるというものです。遠くの景色ほど長距離の大気に阻まれているため拡散する可能性が高く、よって視覚的に前後関係が感じられるというわけです。前者の線遠近法は建築分野、美術分野で使われており、後者の空気遠近法は美術分野で使われています。

![パース法の種類01](/assets/img/2013-03-14/01.png)

![パース法の種類02](/assets/img/2013-03-14/02.png)

![パース法の種類03](/assets/img/2013-03-14/03.png)

![パース法の種類04](/assets/img/2013-03-14/04.png)

## パース法の歴史

次はパース法の歴史を簡単に辿って見ましょう。最も古いパース法が使われた例は、紀元前5世紀の古代ギリシャの舞台美術で、背景パネルに奥行きのある絵を描いたというものだそうです。それ以降も多くの学者が試行錯誤を重ね、1400年代初期に建築家ブルネレスキが全ての建築の線は地平線に収束することに気づき、遠近法を幾何学的に「表現」することに成功しました。その後、15世紀の西洋美術には描かせないテクニックとして使われます。しばらく後になって、文学者アルベルティ著の『絵画論』の中で遠近法を実用的な形で「理論化」に成功し、1474年にピエロ・デラ・フランチェスカが、視野内の全てのものに遠近法を適用する「方法」を確立したとWikipediaに書いていました。そして2013年にお絵描きホーホー論によってパース法が一般層に普及するに至ったそうです。

パース法とは、こんなに大昔から研究されている歴史ある学問なんですね。多くの情報に自由に触れることのできる現代人として、パースの一つも描けないと思うと情けなくなってしまいます。さらに追い打ちをかけるように、かの有名なレオナルド・ダヴィンチには「実践は強固な理論のもとでのみ構築される。遠近法こそその道標であり、入り口でもある。遠近法無しではこと絵画に関して期待できるものは何もない(フリー百科時点Wikipediaより引用)」と断言されてしまいました。これはもうパース法をマスターするしかないでしょう。

## パース法を学ぶ意義

ところで、パース法なんか現代技術の3DCGソフトがあれば勉強するだけ無駄だと思っていませんか？ 確かに正確に遠近感を再現する能力はありますが、自動生成機能があるわけではないのでモデリングするのは結局人間です。それに、モデリングしただけではただの灰色の謎の物体ができるだけなので、ポリゴンにはテクスチャを張り付けることになります。そのテクスチャを描くのは人間です。ただ、各ポリゴンに対して真正面から見た形のテクスチャを描く分にはパースの知識はさほど要りません（どこのテクスチャを描くべきかの判断には熟練が必要です）。しかし、セルアニメーションでは蓄積された背景美術のノウハウを応用し、はじめからパースのかかった背景美術を描いておいて、それをその背景画と同じ視点から3Dモデルに投影するカメラマップという手法を使うことが多いです。（fig.02）このように一部の3DCGは手描き技術の上になっているようなものとも言えます。いずれにせよ、3DCGで作品を作る為にも構想段階では手書きでラフスケッチを描くものです。ハリウッド映画は最終的な映像は実写であるのに、建築デザインのラフスケッチなど見ただけでも腰を抜かしそうなほど写実的な絵が描かれています。パース法というのは、描くための技術ではありますが、イメージを具現化するときや模索するときにその行為に信憑性を持たせるためにも身につけておくべき基礎なんですね。パース法は木炭デッサンと同じくらい重要な技術と言っても過言ではありません。「トーン」で立体感を表現する木炭デッサンとは全く異なる手法で、同じく立体感を「形」で表現するのがパース法です。

![マッピングの種類01](/assets/img/2013-03-14/05.png)

![マッピングの種類02](/assets/img/2013-03-14/06.png)

![マッピングの種類03](/assets/img/2013-03-14/07.png)

今回はパース法の概要を調べただけで終わりましたが、これから取り組む課題は、パース法の手法を習得することではなく、それらをいかに利用するかを考えることです。最終的には人物画のアタリ線を描く位の感覚で、パース線を描いて遠近感をデッサンできるようになることが目標です。次回はパース法の技法を一通り列挙し、さらにパース法を使用する場面も必要なだけ列挙し、「技法」と「シチュエーション」の対戦カードの組合せを考えようと思います。つまり座学回です。