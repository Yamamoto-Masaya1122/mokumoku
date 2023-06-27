# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
### **選択した事業側の課題**

直近一年間で、2回以上もくもく会に参加してくれた人は利用者全体の1%のみ。もくもく会で気の合う仲間を見つけられなかったのではないか？

### **提案内容**

もくもく会の後に交流会（食事会）を開催することができるようにする。

もくもく会では個々の作業に集中するため、コミュニケーションの機会が限られる。なので、他の参加者と思ったより話すことが出来なくて、気の合う仲間を見つけられなかったことが考えられる。なので、気軽に交流の場を作れるような仕組みを作る。

### **実装方針**

- もくもく会の作成時に交流会有or無をタグで選択できるようにする。
- もくもく会の作成時にお店のURLと予算をフォームに入力できるようにする。
- もくもく参加者は詳細画面からもくもく会のみ参加するorもくもく会＆交流会に参加するを選択できる。
- もくもく会一覧画面において、各イベントに交流会有or無のタグをタップするとそのタグで絞り込みが行われるようにする