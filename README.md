# makisaba

巻鯖(makisaba)は､ Webブラウザからの観測を含め､ 各種のプロセスとの交信を記述します｡


# ローカルへのインストール(?)

```
# clone this repository
git clone https://github.com/FreecivJapan/makisaba

# clone submodule and maybe link to newest ID(?)
# (How to update a submodule version to latest ? -- https://github.com/tj/git-extras/pull/80)
git pull --recurse-submodules
git submodule update --remote --recursive

# push because of report newest version of submodule(?)
git push origin master

```


# 仮設常設鯖

maki (i-makinori) による､仮設の常設鯖
- IPアドレス 153.126.215.94, ポート番号 5556


# 方針について

Webからの操作も可能なシステムの作成｡

- Freecivの歴史を紐付けるシステム
  - 歴史立てシステム｡
  - 鯖立て機能｡ 1回の歴史を鯖一回とする｡自動的に歴史も追加される｡
  - 歴史毎に自動生成される掲示板
  - スコアログの生成の自動化｡
  - 変遷のViewer｡
  - チャット､ 統計報告､ 世界地図などなど､ FreecivのClientのobserverによる情報収集と､継続する即時性｡
  - 再度の構造化
  - 奇怪学習によるAIの作成｡


