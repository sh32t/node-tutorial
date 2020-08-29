# Node.jsチュートリアル
## プロジェクトの作成
#### プロジェクトフォルダ直下で下記コマンドを実行する。
```ps1
npm init -y
```
## JavaScriptファイルの作成
#### `sample.js`をプロジェクトフォルダ直下に作成する。
```js
console.log('Hello Node.js');
```
## JavaScriptファイルの実行
```ps1
node sample.js
```
## npm startで実行
#### `package.json`の`"script"`を下記のように書き換える。
```json
  "scripts": {
    "start": "node sample.js"
  },
```
```ps1
npm start
```


### 参考
#### [node.jsを使ってjsファイルを実行する方法](https://q-az.net/node-js-pursue/)
#### [初期化処理を行う！npm initの使い方【初心者向け】](https://techacademy.jp/magazine/16151)
#### [プロジェクトを実行！npm startの使い方【初心者向け】](https://techacademy.jp/magazine/16393)

