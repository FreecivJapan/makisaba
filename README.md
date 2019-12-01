# makisaba

巻鯖(makisaba)は､ Webブラウザからの観測を含め､ 各種のプロセスとの交信を記述します｡


# ローカルへのインストール

```
# clone this repository. and pull submodules.
git clone https://github.com/FreecivJapan/makisaba
git pull --recurse-submodules

# how to let submodule to be newest version of submodules repository locally is...
git submodule foreach git pull origin master

```


# 仮設常設鯖

maki (i-makinori) による仮設の常設鯖の､
- IPアドレスは 153.126.215.94, ポート番号は 5556, 対応する版は2.6.0､です｡


# 今後の方針について

Webからの操作も可能なシステムの作成｡

1. Freecivの歴史を紐付けるシステム
  - 歴史立てシステム｡
  - 鯖立て機能｡ 
    - 1回の歴史を鯖一回(一回のゲーム)とし｡自動的に歴史も追加される｡
  - 掲示板
  - 歴史毎に自動生成される掲示板｡
  - スコアログの自動投稿｡
  - 簡易的なユーザー機能､､､ 似非認証､専用ページ､総覧､編集｡
  - 構造の再設定
1. 他のSNSとの連携
  - Discordへの報告
  - データベースとしてのgithub
  - Githubの専用ユーザーと､編集者･概要･(日時)･などなどを踏まえた コミットログの自動生成｡
1. Freecivの統計収集とFreeciv Client
  - 変遷のViewer｡
  - チャット､ 統計報告､ 世界地図などなど､ FreecivのClientのobserverによる情報収集と､即時性の継続｡
1. クライアント､AI
  - 奇怪学習によるAIの作成｡
  - クライアントの作成｡


