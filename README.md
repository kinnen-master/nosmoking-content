# 禁煙マスター コラム配信リポジトリ

アプリ「禁煙マスター」がコラム記事を取得する配信元です。

- `columns.json` … 全記事のメタデータ＋無料記事の本文（プレミアム本文は含まれません）
- このファイルは **手で編集しない** でください。アプリ開発プロジェクトの
  `content/columns/` で記事(.md)を書き、`python3 build/make_columns.py` で生成し、
  `build/publish_columns.sh` で公開します。

配信URL:
https://raw.githubusercontent.com/kinnen-master/nosmoking-content/main/columns.json
