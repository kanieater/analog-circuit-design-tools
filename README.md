# アナログ回路設計ツール

## フォルダ構成

```
index.html                              ← トップページ（ツール一覧）
tools/
  two-stage-compensation/index.html     ← 2段アンプ位相補償ツール
  mosfet-gm-ro/index.html               ← MOSFET gm・ro 計算機
```

公開後の URL は次のようになります。

- トップページ: `https://<ユーザー名>.github.io/<リポジトリ名>/`
- ツール: `https://<ユーザー名>.github.io/<リポジトリ名>/tools/two-stage-compensation/`

## GitHub Pages での公開手順

1. GitHub アカウントを作成し、右上の「+」→「New repository」で新しいリポジトリを作る（例: `analog-tools`、Public を選択）。
2. リポジトリ画面の「Add file」→「Upload files」で、このフォルダの中身（`index.html` と `tools` フォルダ）をドラッグ＆ドロップし、「Commit changes」を押す。
3. 「Settings」→ 左メニューの「Pages」を開き、Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして「Save」。
4. 1〜2分待つと、同じ画面に公開 URL が表示されます。

リポジトリ名を `<ユーザー名>.github.io` にすると、URL が `https://<ユーザー名>.github.io/` だけになります。

## ツールを追加するとき

1. `tools/` の下に新しいフォルダを作り、その中に `index.html` としてツールを置く。
2. ツールのページ上部に、トップへ戻るリンク `<a href="../../">← ツール一覧</a>` を入れる。
3. トップページ `index.html` の「準備中」カードの前に、既存のカードをコピーしてリンク先・タイトル・説明を書き換える。
4. GitHub にアップロードすると、数分で反映されます。
