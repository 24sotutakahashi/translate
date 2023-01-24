# 書き出した感情を画像で表現するWEBサービス


# プロダクトの概要：

「多くの人が自分の感情を整理しやすくなるようなサービスを創りたい」という想いから、3年次の12月に書き出した感情を画像で表現するWEBサービスを開発しました。

主にDjangoを用いて作りました。
 
 
 また、改良版として[GPT-3 APIを使用して制作したバージョン](https://github.com/24sotutakahashi/translate-by-GPT-3)もあります。

 
 
# 処理の流れの概要
 
①書き出してもらった感情を取得する

↓

②それを朝日新聞APIを用いて要約

↓

③DeepL APIを用いて、要約を英訳

↓

④DALL·E API2を用いて、英訳したものを基に画像を生成

↓

⑤英訳したものと画像を、テンプレート上で表示
# 使用した言語：

Python 

HTML

JavaScript

# 始めた理由

①前提：

年中から小学校低学年のお子さんがボリュームゾーンのプログラミングスクールで講師アルバイトをしています。 
そこでの研修の中で、お子さんが癇癪を起こしてしまうひとつの原因が、「まだ自分の感情を言葉で整理する事が難しい」事であると知りました。 これに衝撃を受けたと同時に、大人にも当てはまる事だなと思いました。 


②理由：

上記の事を、画像の自動生成について知った時に思い出しました。 そこで自分の感情を書き出し、それを画像で表現するサービスがあれば、上手な言語化は難しても自分の感情を整理する機会を作れるかもなと思いました。 これが、今回のプロダクトを作った理由です。

# どれくらいの期間をかけたのか？

 どの自然言語処理モデルを使えるかなど、方針から1人で考えたので、今の状態に至るまで1ヶ月程かかりました。

