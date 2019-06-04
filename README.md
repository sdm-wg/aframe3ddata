# A-Frame 3D Data (gltf)

## Setup

### 1. nodebrew のインストール

[nodebrew のインストール](https://weblike-curtaincall.ssl-lolipop.jp/blog/?p=1630) を参考に nodebrew をインストールして, Node.js と npm をインストールしてください.

### 2. リポジトリの clone とパッケージの install

```bash
$ git clone git@github.com:sdm-wg/aframe3ddata.git
$ cd aframe3ddata
$ npm install
```

### 3. 動作確認

```bash
$ npm run dev
```

これで, ローカルサーバーが起動するので, http://0.0.0.0:9090/ にアクセスしてください

## Development

原則, GitHub flow にそった開発フローです.  
ブランチ名は, [Semantic Commit Messages](https://seesparkbox.com/foundry/semantic_commit_messages) などを参考にしてください.  

あるターミナルで `$ npm run dev` を実行してローカルサーバーを起動しておき,  
別のターミナルでファイルを変更すればオートリロードが実行されます.  

commit 前に ESLint のチェックとビルドがパスするか ? のチェックは必ずしてください

```bash
$ npm run lint && npm run build
```
