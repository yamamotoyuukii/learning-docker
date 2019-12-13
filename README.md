# learning-docker: Dockerの練習

## ミニレポート

### Q1-1: 同じ `docker container run` コマンドを2回実行すると、1回目と2回目で違いはありますか？どう違いますか？

【回答欄】
1回目はダウンロードがあるが、2回目はないため省力されてる
### Q1-2: なぜ違いますか？

【回答欄】
ダウンロードがないから
### Q1-3: `docker container ls` と `docker container ls -a` はどう違いますか？

【回答欄】
-aをつけたすことで作った時間やステータスなどがわかる
### Q1-4: `docker image ls` と `docker container ls -a` はどう違いますか？（間違ってもいいので、自分の考えを述べてください）

【回答欄】
-aをつけたすことで作った時間やステータスなどがわかる
### Q1-5: `ubuntu` イメージでの `cat /etc/issue` の結果をペーストしてください

【回答欄】
Debian GNU/Linux 10 \n \l
### Q1-6: `docker image ls` と `docker container ls -a` はどう変化しましたか？

【回答欄】
違いがない
### Q2-1: `-d` (デタッチド・モード) でコンテナを起動すると、どのような状態になりましたか？

【回答欄】
えらー？がでた
### Q2-2: http://localhost/ をブラウザで開くと、何が表示されましたか？

【回答欄】
Welcome to nginx!
### Q3-1: `docker build -t sample-image .` 実行時に表示されている `building...` は、Dockerfileのどの行から実行されましたか？

【回答欄】
2行目
### Q3-2: `docker run sample-image` を実行すると、どうなりましたか？

【回答欄】
エラーがでた