# 日記を要約して英訳するWEBサービス


▼プロダクトの概要：

3年次の9月に、「自分の感情を整理しやすくなるようなサービスを創りたい」という想いから、日記を要約して英訳するWEBサービスを開発しました。
まだ途中なので、目標、現状、課題に分けて記述します。 

目標:

感情を書き出したらそれを要約し、 それを元に画像を生成するウェブサービスを作成する事。
画像生成には、midjourneyを使う予定です。 そのために、midjourneyに渡す文字は英訳します。

現状:

①書き出してもらった感情を要約し、英訳して返す事は出来ています。
要約は朝日新聞さんの長文要約APIを、英訳にはDeepLさんのAPIを使用しています。
②ボタンをワンクリックすると英訳した要約をコピーし、もうワンクリックするとdiscordを開くように出来ています。

課題:

①英訳した要約を、discordのmidjourneyのチャンネルに自動的に送信できていない。 
②ページのデザインが良くない。

▼使用した言語：
Python 
HTML 
JavaScript

▼始めた理由
①前提：
年中から小学校低学年のお子さんがボリュームゾーンのプログラミングスクールで講師アルバイトをしています。 
そこでの研修の中で、お子さんが癇癪を起こしてしまうひとつの原因が、「まだ自分の感情を言葉で整理する事が難しい」事であると知りました。 これに衝撃を受けたと同時に、大人にも当てはまる事だなと思いました。 
②内容：
上記の事を、画像の自動生成について知った時に思い出しました。 そこで自分の感情を書き出し、それを画像で表現するサービスがあれば、上手な言語化は難しても自分の感情を整理する機会を作れるかもなと思いました。 これが、今回のプロダクトを作った理由です。

▼どれくらいの期間をかけたのか？
 どの自然言語処理モデルを使えるかなど、方針から1人で考えたので、今の状態に至るまで3週間程かかりました。
