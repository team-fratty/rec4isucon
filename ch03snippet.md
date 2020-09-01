# 第3章 ISUCON の練習をしよう！（環境構築編）

3.3.5 構築手順

* リスト 3.1 Ubuntu ユーザー作成
```sh
sudo adduser isucon
cat /etc/passwd | grep isucon
sudo gpasswd -a isucon sudo
su - isucon
timedatectl set - timezone Asia/Tokyo
```


