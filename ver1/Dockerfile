# 0. ubuntu:22.04をベースにする
FROM ubuntu:22.04

# 1. command_tutorialディレクトリをルートディレクトリに作成し
#    その中に（中身が空のファイル）firstvi.txtを作成
RUN mkdir /command_tutorial
RUN touch /command_tutorial/firstvi.txt

# 2. viのインストール
RUN apt update
RUN apt -y install vim