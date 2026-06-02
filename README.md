# 安東健治 Portfolio

映像ディレクター / エディター 安東健治の静的ポートフォリオサイトです。

## Vercel Hobby Plan Deploy

このサイトは HTML / CSS / 画像だけで構成された静的サイトです。
Vercel では `Framework Preset` を `Other` にして、そのまま公開できます。

### GitHub にアップするファイル

`kj-polacine` フォルダの中身を、GitHub リポジトリのルートに置いてください。

```text
index.html
vercel.json
README.md
.gitignore
assets/
```

### Vercel の設定

- Framework Preset: `Other`
- Build Command: 空欄
- Output Directory: 空欄
- Install Command: 空欄

### 公開手順

1. GitHub にこのサイトのコードをアップする
2. Vercel にログインする
3. `Add New Project` を押す
4. GitHub のリポジトリを選ぶ
5. `Framework Preset` が `Other` になっていることを確認する
6. `Deploy` を押す
7. `https://xxxxx.vercel.app` のURLで公開完了

## Local Preview

```bash
python3 -m http.server 4180 --bind 127.0.0.1
```

ブラウザで `http://127.0.0.1:4180/` を開いて確認できます。
