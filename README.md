# nuxt-layer-sample

## 概要

- Nuxt3 の Layers を使用したサンプルです

## 実行環境

- Node.js - 20.x
- Yarn - 1.22.x

## 使用ライブラリ

- nuxt - 3.6.x

## 動作確認

```bash
# パッケージインストール
$ yarn

# nuxt-app実行 - http://localhost:3000, http://localhost:3000/layer1, http://localhost:3000/layer2
$ yarn workspace @nuxt-layer-sample/nuxt-app run dev

# layer1実行 - http://localhost:3000/layer1
$ yarn workspace @nuxt-layer-sample/layer1 run dev

# layer2実行 - http://localhost:3000/layer2
$ yarn workspace @nuxt-layer-sample/layer2 run dev
```

## ディレクトリ構成

```
├── layer-lib     ライブラリ用のNuxt Layer
├── layer1        /layer1用のNuxt Layer
├── layer2        /layer2用のNuxt Layer
└── nuxt-app      Nuxt起動用
```

## 参考 URL

- https://nuxt.com/docs/getting-started/layers
