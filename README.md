# linux-server-setup
# Linuxサーバー構築

## 概要
WSL2を使ってUbuntu上にNginxのWebサーバーを構築しました。

## 環境
- OS: Ubuntu 24.04 (WSL2)
- Webサーバー: Nginx 1.24.0

## やったこと
- Nginxのインストール
- Nginxの起動・動作確認
- HTMLファイルの編集

## 手順
### 1. パッケージの更新
sudo apt update

### 2. Nginxのインストール
sudo apt install nginx -y

### 3. Nginxの起動
sudo systemctl start nginx

### 4. ブラウザで確認
http://localhost にアクセスして「Welcome to nginx!」を確認

## 詰まったところ
- 日本語を表示したら文字化けした
- meta charsetをUTF-8に設定して解決

## SSH設定
SSH接続の設定完了
