# 🦭 アザラシフェイス

カメラで顔を検出して、アザラシの顔に置き換えるWebアプリです。

## 使い方

1. このURLをiPhoneのSafariで開く
2. カメラの使用を許可する
3. 顔をカメラに向けるとアザラシになる 🦭

## 仕組み

- [face-api.js](https://github.com/vladmandic/face-api) — ブラウザ内で顔検出（TensorFlow.js）
- Canvas API — アザラシ顔をリアルタイムで重ね描き
- サーバー不要 — GitHub Pages で静的配信

## GitHub Pages での公開手順

1. このリポジトリの **Settings** → **Pages**
2. Source: **Deploy from a branch** → `main` / `/(root)`
3. Save → 数分後に `https://<username>.github.io/<repo>/` で公開
