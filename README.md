# aozora-vue

A trial of a new user interface for Aozora Bunko contents using [Nuxt](https://nuxtjs.org/)

[Nuxt](https://ja.nuxtjs.org/)を使った青空文庫の新たなユーザインターフェイスの試みです。

[https://aozora-vue.ksato9700.com](https://aozora-vue.ksato9700.com)

## Features
### 実現済みの機能
* 作品名、著者名での検索
* 作品を読む（作品リストから一つをクリック・タップするとXHTML版を表示）
* 作品をお気に入りに入れる（作品リストで☆アイコンをクリック）
* 作品をお気に入りから外す（作品リストで★アイコンをクリック）
* 作品の詳細を表示（検索結果のⓘアイコンをクリック）
* お気に入りリストを表示（ツールバーの★をクリック、あるいは左側のメニューから選ぶ）
・青空文庫の基本情報を表示（ツールバーのⓘをクリック、あるいは左側のメニューから選ぶ）

### 実現したい機能
* 新着情報の表示
* ランキングの表示
* 検索結果のpagenation (今は10作品のみを表示)
* 著者名からの作品表示
* 複数著者作品のサポート
* ユーザログインして、
  * お気に入りの管理
  * 閲覧履歴の管理


## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```
