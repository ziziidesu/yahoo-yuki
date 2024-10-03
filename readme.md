

# 警告

このインスタンス内の掲示板にはシード値が漏れるセキュリティ上のバグがあります。

現在、セキュリティの警告を開発者に送っていますが、2024/10/3 8:00時点での応答がありません。

掲示板のコードは高度に暗号化されたWebAssemblyが使用され、同じく暗号化されたサーバー側のプログラムが使用されているためにこちらからは手が出せない状態です。

掲示板を使わないか、攻撃への十分な備えをしてからご利用ください。

# 偽造ページの作成
このYuki Youtubeの偽造画面には天気予報が表示されます。

JF6DEUが偽造画面を作成しました。

# 注意点

掲示板に接続するため、定期的にインスタンスを再起動してください。


# Renderを使用する場合の手順  

1~4の作業をやらないと、自動でURLが`yuki-tangolevel-4桁の英数字.onrender.com`になります。 

1. githubアカウントを作成する 

1. リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします) 

1. import codeを押して [https://github.com/mochidukiyukimi/Yuki-Youtube-slim/](https://github.com/mochidukiyukimi/Yuki-Youtube-slim/) と入力 

1. render.yamlを開いて編集(鉛筆のマーク)を押し、`name`の横にある`yuki-youtube-slim`をサイトのurlの最初の部分にしたい文字列に変更する。(`yuki-y`だったらurlは`https://yuki-y.onrender.com`になる)

1. Deploy to renderボタンを押し、Service Group Nameに適当な文字列を入れてapplyを押す※事前にrenderのアカウントを作っておく

<a href="https://render.com/deploy?repo=https://github.com/JF6DEU/yukiTube.git">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
