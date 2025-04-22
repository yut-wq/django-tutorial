# Django チュートリアル with uv

## 各種コマンド

### Django のバージョン確認

`uv run -m django --version`

### Django-Admin

`uv run -- django-admin startproject mysite djangotutorial`

### 開発サーバーの実行

`uv run ./djangotutorial/manage.py runserver`

`uv run ./manage.py runserver`

### テストの実行

`uv run ./manage.py test polls`
