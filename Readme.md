# Sass Webpackで環境構築手順
## 1. package.json の作成
以下のコマンドを打つ
```
npm init -y
npm install
```
## 2. src にscssファイル作成し、同ディレクトリのapp.jsに追加したscssファイルを追記する
例
```
import './test.scss';
```
## 3. scssをcssにコンパイル
```
npm run build
```