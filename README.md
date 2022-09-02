# データベース更新手順
- 1.更新内容をDB担当者(水本)にDiscordで連絡する

- 2.DB担当者が作成したdumpファイルを使って更新する

  - DB:examplatform がない場合は`mysqladmin -u ユーザー名 -p create examplatform` でDBを作成する
  
  - 次の `mysql -u ユーザー名 -p examplatform < examplatform.dump.sql` を入力して、更新する
  
- 3.更新したらDiscordのChannelsに完了報告をする
