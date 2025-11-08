# Python & Flask チュートリアル

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.0+-green.svg)](https://flask.palletsprojects.com/)

Python基礎からFlask Webアプリ開発、データベース連携、デプロイまでをカバーする包括的なチュートリアルサイトです。

[English](README.md) | 日本語

## 概要

このリポジトリには、Pythonプログラミングの基礎とFlask Webアプリケーション開発を学ぶための完全なチュートリアルサイトが含まれています。初心者から中級者向けに設計されており、実践的なコード例、詳細な解説、ハンズオンプロジェクトが含まれています。

**公開サイト**: [http://kklab.mobi/Python_Flask_Tutorial/](http://kklab.mobi/Python_Flask_Tutorial/)

## コンテンツ

### 1. Python初級チュートリアル

Python基礎を網羅する11章構成の完全ガイド：

- **第1章**: Hello World - 最初のPythonプログラム
- **第2章**: 変数とデータ型
- **第3章**: 文字列操作
- **第4章**: リストとタプル
- **第5章**: 辞書とセット
- **第6章**: 制御フロー（if、for、while）
- **第7章**: 関数
- **第8章**: モジュールとパッケージ
- **第9章**: クラスとオブジェクト指向プログラミング
- **第10章**: ファイル操作
- **第11章**: エラー処理と例外

**利用可能な形式**：
- インタラクティブHTML: `Python_Beginner_Tutorial_Complete.html`
- Markdown: `Python_Beginner_Tutorial_Complete.md`
- 実行可能なサンプル: `python_beginner_tutorial/examples/`

### 2. Flask Webアプリ開発チュートリアル

Flaskを使ったWebアプリケーション構築の実践ガイド：

- **環境構築**: 環境セットアップと基本的なFlaskアプリ
- **ルーティング**: URLパターン、HTTPメソッド、動的ルーティング
- **テンプレート**: Jinja2テンプレートエンジン、テンプレート継承
- **フォーム**: フォーム処理、バリデーション、ファイルアップロード
- **データベース**: SQLAlchemy連携、CRUD操作
- **実践例**: 完全に動作するアプリケーション

**利用可能な形式**：
- インタラクティブHTML: `Flask_Tutorial_Complete.html`
- Markdown: `Flask_Tutorial_Complete.md`
- 動作するアプリ: `flask_tutorial/`

## リポジトリ構造

```
Python_Flask_Tutorial/
├── index.html                              # メインランディングページ
├── LICENSE                                 # MITライセンス
│
├── Python_Beginner_Tutorial_Complete.html  # Pythonチュートリアル（HTML）
├── Python_Beginner_Tutorial_Complete.md    # Pythonチュートリアル（Markdown）
├── python_beginner_tutorial/
│   └── examples/                           # 実行可能なPythonサンプル
│       ├── 01_hello_world.py
│       ├── 02_variables_and_types.py
│       ├── 03_strings.py
│       ├── 04_lists_and_tuples.py
│       ├── 05_dictionaries_and_sets.py
│       ├── 06_control_flow.py
│       ├── 07_functions.py
│       ├── 08_modules.py
│       ├── 09_classes_and_oop.py
│       ├── 10_file_handling.py
│       └── 11_error_handling.py
│
├── Flask_Tutorial_Complete.html            # Flaskチュートリアル（HTML）
├── Flask_Tutorial_Complete.md              # Flaskチュートリアル（Markdown）
├── flask_tutorial/
│   ├── app.py                              # 基本的なFlaskアプリ
│   ├── routes_example.py                   # ルーティング例
│   ├── template_example.py                 # テンプレート例
│   ├── forms_example.py                    # フォーム処理
│   ├── database_example.py                 # データベース連携
│   ├── requirements.txt                    # Python依存関係
│   ├── README.md                           # Flaskチュートリアルガイド
│   ├── templates/                          # HTMLテンプレート
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── about.html
│   │   ├── contact.html
│   │   ├── forms/                          # フォームテンプレート
│   │   │   ├── index.html
│   │   │   ├── simple.html
│   │   │   ├── register.html
│   │   │   ├── contact.html
│   │   │   ├── upload.html
│   │   │   └── result.html
│   │   ├── db/                             # データベーステンプレート
│   │   │   ├── index.html
│   │   │   ├── users.html
│   │   │   ├── user_detail.html
│   │   │   ├── add_user.html
│   │   │   ├── post_detail.html
│   │   │   ├── add_post.html
│   │   │   └── edit_post.html
│   │   └── macros/                         # 再利用可能なテンプレートマクロ
│   │       └── forms.html
│   └── static/                             # 静的ファイル
│       ├── css/
│       └── js/
│
├── convert_to_html.py                      # チュートリアル変換スクリプト
└── convert_python_to_html.py               # Pythonチュートリアル変換
```

## はじめ方

### 前提条件

- Python 3.7以上
- pip（Pythonパッケージインストーラー）
- テキストエディタまたはIDE（VS Code、PyCharmなど）

### Pythonサンプルの実行

1. Pythonサンプルディレクトリに移動：
```bash
cd python_beginner_tutorial/examples
```

2. 任意のサンプルを実行：
```bash
python 01_hello_world.py
```

### Flaskアプリケーションの実行

1. Flaskチュートリアルディレクトリに移動：
```bash
cd flask_tutorial
```

2. 仮想環境を作成：
```bash
python -m venv venv

# Windowsで有効化
venv\Scripts\activate

# macOS/Linuxで有効化
source venv/bin/activate
```

3. 依存関係をインストール：
```bash
pip install -r requirements.txt
```

4. 基本的なFlaskアプリを実行：
```bash
python app.py
```

5. ブラウザで `http://localhost:5000` にアクセス

### 各種Flaskサンプルの実行

各Flaskサンプルは異なる機能をデモンストレーションします：

- **基本アプリ**: `python app.py` - シンプルなFlaskアプリケーション
- **ルーティング**: `python routes_example.py` - URLルーティングパターン
- **テンプレート**: `python template_example.py` - Jinja2テンプレート
- **フォーム**: `python forms_example.py` - フォーム処理とバリデーション
- **データベース**: `python database_example.py` - SQLAlchemy CRUD操作

## 特徴

- **初心者フレンドリー**: 明確な説明とステップバイステップの例
- **包括的**: 基礎から応用トピックまでカバー
- **実践的**: 実際のコード例とプロジェクト
- **複数の形式**: HTML、Markdown、実行可能なコード
- **日本語対応**: 完全日本語チュートリアル
- **ハンズオン**: 実行・変更可能なインタラクティブな例
- **最新スタック**: 最新のPythonとFlaskバージョン

## 学習パス

### Python初心者向け

1. `Python_Beginner_Tutorial_Complete.html` から始める
2. 各章を順番に進める
3. `python_beginner_tutorial/examples/` のサンプルコードを実行
4. サンプルを変更して実験する

### Flask学習者向け

1. まずPython初級チュートリアルを完了する
2. `Flask_Tutorial_Complete.html` を読む
3. `flask_tutorial/README.md` のセットアップ手順に従う
4. 各Flaskサンプルアプリケーションを実行
5. 学んだパターンを使って独自のプロジェクトを構築

## カバーするトピック

### Python基礎

- 基本構文とプログラム構造
- データ型：文字列、数値、リスト、辞書
- 制御構造：条件分岐とループ
- 関数とモジュール
- オブジェクト指向プログラミング
- ファイルI/O操作
- 例外処理
- ベストプラクティスとコーディング規約

### Flask Webアプリ開発

- Flaskアプリケーション構造
- URLルーティングとビュー関数
- HTTPメソッド（GET、POSTなど）
- Jinja2によるテンプレートレンダリング
- テンプレート継承とマクロ
- フォーム処理とバリデーション
- ファイルアップロード
- SQLAlchemyによるデータベース連携
- ORMモデルとリレーションシップ
- CRUD操作
- セッション管理
- エラー処理
- RESTful API基礎

## 貢献

貢献を歓迎します！エラーを見つけた場合や改善の提案がある場合：

1. リポジトリをフォーク
2. フィーチャーブランチを作成
3. 変更を加える
4. プルリクエストを送信

## ライセンス

このプロジェクトはMITライセンスの下でライセンスされています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。

## リソース

- [Python公式ドキュメント](https://docs.python.org/ja/)
- [Flask公式ドキュメント](https://flask.palletsprojects.com/)
- [Jinja2ドキュメント](https://jinja.palletsprojects.com/)
- [SQLAlchemyドキュメント](https://www.sqlalchemy.org/)
- [WTFormsドキュメント](https://wtforms.readthedocs.io/)

## 作者

Created by katzkawai

## 謝辞

- Python Software Foundation
- Flask開発チーム
- オープンソースコミュニティ

---

**Happy Coding with Python!** 🐍🚀
