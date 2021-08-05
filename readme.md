# webpack 基本設定

## webpack の設定

src 内の js/css/scss/img ファイルを index.js に出力して dist にコンパイルさせる

## 使い方

0. node.js インストール
1. `cd` でディレクトリに移動
2. `npm init -y`で`package.json`を生成
3. `npm i -D webpack webpack-cli`で webpack 本体をインストール
   （Sass や CSS を使う場合は `npm i -D webpack webpack-cli sass-loader sass style-loader css-loader`を実行）

---

4. `package.json`を編集
5. `webpack.config.js`を編集

---

6. `index.js`を起点に src フォルダを編集

---

- `npm i -D webpack webpack-cli webpack-dev-server`実行後、`npm run start`でローカルサーバ実行
- `npx webpack`でコンパイル
