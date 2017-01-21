# OAuthAccessTokenOnLambda

OAuthRequestTokenOnLambdaで得たoauth_tokenとoauth_verifierから、oauth_tokenとoauth_verifierを発行します。

# 使い方
コンシューマキーとコンシューマシークレットをセットします。

```
const consumer_key = YOUR_APP_CONSUMER_KEY;
const consumer_secret = YOUR_APP_CONSUMER_SECRET;
```

# リクエストパラメータ

実行時、OAuthRequestTokenOnLambdaで得たoauth_tokenとoauth_verifierをJSON形式で投げてください。
```
{
  "oauth_token": "HOGEHOGEHOGE",
  "oauth_verifier": "FUGADUGADUGA"
}
```

# 結果
oauth_tokenとoauth_verifierが帰ってきます。
