# UniChat - 大学サークル向けミニTwitter風アプリ

大学のサークル等、小規模のコミュニティで利用可能なTwitter風SNSウェブアプリケーション

## 概要

**UniChat** は、大学のサークルやゼミなど、**少人数グループ向け**のシンプルなチャット・投稿アプリです。  
Twitter風のタイムライン形式で、ユーザーがログインして自由につぶやきを投稿・閲覧できます。

## 主な機能

- **ユーザー登録/ログイン**: アカウント作成とログイン機能
- **投稿機能**: 140文字までのテキスト投稿
- **タイムライン**: 全ユーザーの投稿を時系列で表示
- **マイページ**: 自分の投稿のみを表示

## 技術スタック

- **バックエンド**: Python/Flask
- **データベース**: SQLite + SQLAlchemy
- **認証**: Flask-Login
- **フロントエンド**: HTML/CSS/Jinja2/Bootstrap

## 開発環境セットアップ

1. リポジトリをクローン
```
git clone https://github.com/yourusername/unichat.git
cd unichat
```

2. 仮想環境を作成し、依存関係をインストール
```
python -m venv venv
source venv/bin/activate  # Windowsの場合: venv\Scripts\activate
pip install -r requirements.txt
```

3. アプリケーションを実行
```
flask run
```

4. ブラウザでアクセス: http://127.0.0.1:5000/

## ライセンス

[MIT License](LICENSE)
