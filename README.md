# sample-jenkins

1. サーバーを起動
```
docker compose up -d
```

2. 生成された Administrator password を確認

```
docker compose exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

3. ブラウザで http://localhost:8080 にアクセス

4. 画面に従って設定
    - Administrator password は手順2のものを入力
