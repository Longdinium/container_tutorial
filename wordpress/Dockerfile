# 0. wordpress:6.1.1-php8.2-apacheをベースにする
FROM wordpress:6.1.1-php8.2-apache

# 1. command_tutorialディレクトリをルートディレクトリに作成して
#    そのなかにfirstvi.txtを作成
RUN mkdir /command_tutorial
RUN touch /command_tutorial/firstvi.txt

# 2. viのインストール
RUN apt update
RUN apt -y install vim

# X.

#HTTPS接続は考慮する必要ありません。HTTP接続のみで用意してください