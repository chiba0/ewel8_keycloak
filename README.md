# read me
## 参考URL
https://zenn.dev/emp_tech_blog/articles/996920de0b93b7

## keycloak 実行(docker 実行)
- chiba@chiba:~/keycloak$ docker-compose up
- http://localhost:8880/
   - admin/admin

## docker 止める
- docker-compose down

## mysql接続
- docker exec -it コンテナ名 mysql -u{ユーザー名} -p{パスワード}
`docker exec -it mysql mysql -ukeycloak -ppassword`

