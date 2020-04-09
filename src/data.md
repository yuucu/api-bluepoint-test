# Data Structures

## UserData
+ id: 1 (number) - Unique identifier
+ screen_name: 名無しさん(string) - ユーザの名前
+ screen_id: nanasi(string)  - ユーザのid
+ description: こんにちは、ななしです。(string)  - ユーザの紹介文
+ avator_image_url: https://example.s3.~(string)  - s3にあるユーザトップ画像のURL
+ header_image_url: https://example.s3.~(string)  - s3にあるユーザヘッダー画像のURL
+ password: password(string) - 暗号化されたパスワード
+ mail: test@example.com(string) - メールアドレス
+ token:  abcdefg(string) - トークン
+ created_at: 2020/04/09 10:20:30(string) - ユーザが作成された時間
+ updated_at: 2020/04/09 10:20:30(string) - ユーザがアップデートされた時間

## UserList (array)
+ (UserData)

## TweetData
+ id: 1 (required, number) - Unique identifier
+ user_id: 1 (required) - ユーザの名前
