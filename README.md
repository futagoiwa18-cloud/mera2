# 滅乱忍伝

SFCくらいの低解像度感で遊ぶ、16:9横スクロール忍者アクションです。キャンバス実解像度は852x480で、キャラクター、背景、橋上ステージ、都市夜景は細かいピクセル描写を追加しています。

## 遊び方

- 移動: ← →
- ジャンプ: Z / Space
- 斬撃: X
- 手裏剣: C
- 開始・再挑戦: Enter / Space

ブラウザの仕様により、BGMとSEはゲーム開始操作のあとに鳴ります。

## GitHub Pagesで公開する

このリポジトリは静的ファイルだけで動きます。

1. GitHubでリポジトリを作成します。
2. `index.html`、`README.md`、`.nojekyll` をリポジトリ直下に置きます。
3. GitHubの `Settings` → `Pages` を開きます。
4. `Build and deployment` で `Deploy from a branch` を選びます。
5. `Branch` を `main`、フォルダを `/root` にして保存します。

しばらく待つと、次のURLで公開されます。

```text
https://<GitHubユーザー名>.github.io/<リポジトリ名>/
```

## ファイル構成

```text
.
├── index.html
├── README.md
└── .nojekyll
```
