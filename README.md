# アプリケーション名
cards-memory-easy

# アプリケーション概要
神経衰弱ゲームです。
同じ数字の組み合わせを１０組揃えると、ゲームクリアです。

# URL
http://52.199.48.20/

# テスト用アカウント
・Basic認証ID： admin
・Basic認証パスワード： 12345678

# 利用方法
・画像をクリックして、カードを裏返し、数字を表示します。

・カードを２回めくり、同じ数字の場合、裏返しのままになります。

・めくったカードの数字が異なる場合、１秒後に元の画像に戻ります。

・１０組揃えるとゲームクリアとなり、「もう一度遊ぶ」ボタンが表示されます。

・「もう一度遊ぶ」ボタンをクリックすると、カードの状態や経過時間がリセットされます。

# アプリケーションを作成した背景
・オリジナルアプリ作成にあたり、JavaScriptを使用して、非同期通信を実装したアプリを作成したいと思ったため。

・ゲーム作成を通じて、条件分岐のコードを記述する力を高めたいと思ったため。
# 洗い出した要件
以下、要件を定義したシートのURLです。
https://docs.google.com/spreadsheets/d/1n6hXzzoKsQN0U5_PhFXmSC5hxSuLiUHC6laWQqFngb8/edit#gid=2048512610

# 実装した機能についての画像やGIFおよびその説明
[![Image from Gyazo](https://i.gyazo.com/a9312f4df88c98391705477c752ba5aa.gif)](https://gyazo.com/a9312f4df88c98391705477c752ba5aa)

[![Image from Gyazo](https://i.gyazo.com/eabe6b6b66fee24d7356b1f93484a9bc.gif)](https://gyazo.com/eabe6b6b66fee24d7356b1f93484a9bc)

[![Image from Gyazo](https://i.gyazo.com/3105034ab58c13bc55405c5b96d70cf3.gif)](https://gyazo.com/3105034ab58c13bc55405c5b96d70cf3)

[![Image from Gyazo](https://i.gyazo.com/428ddc6a27d2aa8e72f2984d2abac845.gif)](https://gyazo.com/428ddc6a27d2aa8e72f2984d2abac845)

# 実装予定の機能
・同じ数字が揃った時、数字が異なった時、すべてのカードを裏返しゲームクリアした時に、音声を再生することです。

# データベース設計
・データベースを使用していないため、省略させて頂きます。

# 画面遷移図
・トップページのみのため、省略させて頂きます。

# 開発環境
・言語：Ruby、JavaScript
・フレームワーク：Ruby on Rails

# ローカルでの動作方法
・以下のコマンドを順に実行して下さい。
% git clone https://github.com/e-t-21/cards-memory-easy.git
% cd cards-memory-easy
% bundle install

# 工夫したポイント
・直感で操作できるアプリになるように作成しました。

・スマートフォンでの表示に対応できるよう、レスポンシブ対応を行いました。

# 改善点
・URLにアクセスすると、経過時間が動き出してしまいます。アクセスした直後の場合、スタートボタンを設け、アクセス直後に経過時間が動かないようにします。

# 制作時間
・約９時間