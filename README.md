# Twitter Card Audio Player

[Twitter Card のドキュメント](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/overview/player-card) を読んでいたら、  
誰でも Twitter 埋め込みプレイヤーを作れるっぽいことがわかって、「よっしゃ、試してみよう」とやったもの。

本当にできたのでびっくりしてる。

PCのWebブラウザから見るぶんには見やすいけれど、  
スマホから見る場合は iframe の中身側のページに飛んでしまうので、  
Web Audio API を使うことでいい感じに遷移してあげたほうが良さそうだ。

<img src="ss.png">
