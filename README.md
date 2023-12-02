# ウェブスクレイピングプロジェクト

このリポジトリは、Google Colabを使用して特定のウェブサイトから情報をスクレイピングするプロジェクトのためのものです。本プロジェクトでは、Pythonを使用してウェブページから特定の要素を抽出し、特定の条件（例: 特定のキーワードの存在）に基づいてデータを収集します。

## プロジェクトの目的

- **目的**: 特定のキーワード（例: 「ハンド」）を含むウェブページを特定し、そのURLを収集する。
- **技術スタック**: Python、Google Colab、BeautifulSoup、Requests。

## セットアップ

1. **Google Colabにアクセス**: [Google Colab](https://colab.research.google.com/)にアクセスし、新しいノートブックを作成します。
2. **必要なライブラリのインストール**: `beautifulsoup4`と`requests`ライブラリをインストールします。
   ```python
   !pip install beautifulsoup4 requests
