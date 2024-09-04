# TODOアプリ

・Gin  
・Gorm  

## 実行方法

・dockerコンテナの立ち上げ  
```bash
root@DESKTOP-RTPGFSE:~/gin_todo_app# docker compose up
```
  
・DBとの接続とmain.goの実行  
```bash
root@DESKTOP-RTPGFSE:~/gin_todo_app# DB=gin_todo_app DB_USER=root DB_PASSWORD=password DB_HOST=localhost DB_PORT=3306 go run .
```
  
http://localhost:8000/index にアクセスして画面が表示されれば成功  

![localhost_8000_index-Google-Chrome-2024-09-03-17-02-53](https://github.com/user-attachments/assets/55f7d77d-0d3f-43fc-b28e-03ce2e1ad766)

