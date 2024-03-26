# 1．Re:Earthへのログイン

## ログイン

- [https://app.reearth.io/](https://app.reearth.io/)にアクセスし、ログインID・パスワードを入力して「ログイン」をクリック
- アカウントを持っていない場合は、新規作成する

![](../resources/userMan/Untitled.png)

# 2．ワークスペースの選択

## ワークスペース

- ワークスペース左上の「ユーザー名」をクリックし、「ワークスペース」からプロジェクトを作成したいワークスペースを選択

![](../resources/userMan/Untitled%201.png)

# 3．classicプロジェクトでのデータ作成・エクスポート

## classicプロジェクトの作成

- ワークスペースの「クイックスタート」から「新規プロジェクト作成」をクリック

![](../resources/userMan/Untitled%202.png)

- プロジェクトタイプから「classic」をクリック

![](../resources/userMan/Untitled%203.png)

- プロジェクト名、プロジェクト概要（任意）、サムネイル画像（任意）を入力し、「作成」をクリック

![](../resources/userMan/Untitled%204.png)

## マーカー/インフォボックスのデータ作成

- 中央パネルのマーカーアイコンを、3Dマップ上のマーカーを設置したい位置にドラッグ＆ドロップ
- 設置したマーカーを選択した状態で左パネルに表示される設定パネルから、スタイルの変更を行う

![](../resources/userMan/Untitled%205.png)

- 設置したマーカーを選択した状態で左パネルのタブ「インフォボックス」をクリックし、「インフォボックスを作成」をクリック

![](../resources/userMan/Untitled%206.png)

- マーカーのインフォボックスの内容やスタイルを編集

![](../resources/userMan/Untitled%207.png)

## マーカー/インフォボックスのデータエクスポート（※インフォボックスもBetaに取り込みたい場合）

- 下記リンクより、プラグインをダウンロード
  - Export makers to GeoJSON（GitHubのプラグインデータリンクを貼る）

- 画面上部のプロジェクト名をクリックし、「プラグイン」をクリック

![](../resources/userMan/pc01.png)

- 表示されたプラグイン管理画面で「個人インストール済み」をクリックし、「PCからZipファルをアップロード」をクリック

![](../resources/userMan/pc02.png)

- インストールしたいプラグインを選択し、アップロード

![](../resources/userMan/pc03.png)

- 管理画面の「インストール済み」一覧にアップロードしたプラグインが表示されていることを確認し、画面左上の編集ボタンをクリックしエディターに戻る

![](../resources/userMan/pc04.png)

- 左パネル「ウィジェット」の＋ボタンをクリックし、追加したいプラグインをクリック

![](../resources/userMan/pc05.png)

- 「ウィジェット」の▼ボタンをクリックし、プラグインが追加されているかを確認できる

![](../resources/userMan/pc06.png)

- 右パネル「レイヤー」でフォルダアイコンをクリックしてフォルダを作成
- エクスポートしたいマーカーをすべて作成したフォルダ内にドラッグで移動

![](../resources/userMan/Untitled%208.png)

- 中央のマップ画面左上にあるエクスポート機能のアイコンをクリック

![](../resources/userMan/Untitled%209.png)

- エクスポートしたいマーカーが格納されたフォルダを選択し、「Export to GeoJSON」をクリックし、マーカー/インフォボックスのデータをエクスポート

![](../resources/userMan/Untitled%2010.png)

## マーカーのデータエクスポート（※インフォボックスをBetaで使用しない場合）

- 右パネル「レイヤー」でフォルダアイコンをクリックしてフォルダを作成
- エクスポートしたいマーカーをすべて作成したフォルダ内にドラッグで移動

![](../resources/userMan/Untitled%208.png)

- 右パネルのアイコンリストから「エクスポート」をクリックし、ファイル形式「GeoJOSN」をクリック

![](../resources/userMan/Untitled%2011.png)

- 「エクスポート」をクリック

![](../resources/userMan/Untitled%2012.png)

# 4．Betaプロジェクトの作成

## Betaプロジェクトの作成

- ワークスペースの「クイックスタート」から「新規プロジェクト作成」をクリック

![](../resources/userMan/Untitled%202.png)

- プロジェクトタイプから「Beta」をクリック

![](../resources/userMan/Untitled%2013.png)

- プロジェクト名、プロジェクト概要（任意）、サムネイル画像（任意）を入力し、「作成」をクリック

![](../resources/userMan/Untitled%2014.png)

# 5．Betaプロジェクトのシーン設定

## タイルマップ設定

- 「マップエディター」の左パネル「タイル」をクリックし、右パネルのタイル一覧から「Default」をクリック
- 表示される設定メニューの「Tile type」から変更したいタイルを選択する（デフォルトでは衛星画像が設定されている）

![](../resources/userMan/Untitled%2015.png)

## 地形（Terrain）設定

- 「マップエディター」の左パネル「地形」をクリック
- 右パネルの「有効化」をオンにして地形を有効化
- 「Terrain type」を「Cesium Ion」に変更し、表示される設定項目から以下の通り入力
    - Asset ID: `770371`
    - Access token: `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiI5N2UyMjcwOS00MDY1LTQxYjEtYjZjMy00YTU0ZTg5MmViYWQiLCJpZCI6ODAzMDYsImlhdCI6MTY0Mjc0ODI2MX0.dkwAL1CcljUV7NA7fDbhXXnmyZQU_c-G5zRx8PtEcxE`
    
    ![](../resources/userMan/Untitled%2016.png)
    

## 3Dマップの陰影表現の設定

- 「マップエディター」の左パネル「地球」をクリック
- 右パネル「Globe Shadow」を有効化すると、建物モデルの陰影表現が追加される（描画が重くなる可能性があるので注意）

![](../resources/userMan/Untitled%2017.png)

## 空の表現設定

- 「マップエディター」の左パネル「空」をクリック
- 3Dマップの背景の空の描画設定を変更できる。（デフォルトではすべてオン）
    - Sky BOX：星の描画
    - Sun：太陽の描画
    - Moon：月の描画
    - Sky Atmosphere：大気の描画
    
    ![](../resources/userMan/Untitled%2018.png)
    

## 初期カメラ位置設定（※ストーリーテリングの初期位置とは異なる）

（※）プロジェクトを更新した際に最初に表示される位置を設定。「ストーリーテリング」の初期位置とは異なるので留意

- 「マップエディター」の左パネル「カメラ」をクリック
- 3Dマップを操作し、初期位置に設定したい位置にカメラを調整
- 右パネル「キャプチャ」をクリックし、表示される設定画面右下の「キャプチャ」をクリック

![](../resources/userMan/Untitled%2019.png)

# 6.Betaエディターへのプラグイン読み込み・設定
## 本ユースケースで使用するプラグイン
- 下記リンクより、プラグインをダウンロード
  - Classical marker infobox（GitHubのプラグインデータリンクを貼る）
  - 3D Tiles feature inspector（GitHubのプラグインデータリンクを貼る）

## プラグインのインストール・設定
- 画面上部のプロジェクト名をクリックし、「プラグイン」をクリック

![](../resources/userMan/pb01.png)

- 表示されたプラグイン管理画面で「個人インストール済み」をクリックし、「PCからZipファルをアップロード」をクリック

![](../resources/userMan/pb02.png)

- インストールしたいプラグインを選択し、アップロード

![](../resources/userMan/pb03.png)

- 管理画面の「インストール済み」一覧にアップロードしたプラグインが表示されていることを確認し、画面左上の編集ボタンをクリックしエディターに戻る

![](../resources/userMan/pb04.png)

- エディター右上の「ウィジェット」をクリックし、ウィジェットエディターに移動
- ウィジェットエディター内右上の追加ボタンをクリックし、インストールしたプラグインを追加

![](../resources/userMan/pb05.png)

- 追加したプラグインのうち、設定を変更したいものをクリックするとインスペクターが表示される

![](../resources/userMan/pb06.png)

# 7．レイヤーの読み込み

## 3D Tilesの読み込み

- 12/9ワークショップにて使用する3D TilesのURLは以下の通り
    - 都市モデル（LOD2）：[https://assets.cms.plateau.reearth.io/assets/f1/ddaa47-16ef-46f7-98b9-1cc76ca76bac/bldg_lod2_no_texture/tileset.json](https://assets.cms.plateau.reearth.io/assets/f1/ddaa47-16ef-46f7-98b9-1cc76ca76bac/bldg_lod2_no_texture/tileset.json)
    - 建物モデル（1街区）：[https://assets.cms.plateau.reearth.io/assets/2c/c6fe5c-192b-4444-b741-695f872aede1/1gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/2c/c6fe5c-192b-4444-b741-695f872aede1/1gaiku_231204/tileset.json)
    - 建物モデル（2街区）：[https://assets.cms.plateau.reearth.io/assets/62/a7a2eb-5151-409f-abd1-820f5243d28b/2gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/62/a7a2eb-5151-409f-abd1-820f5243d28b/2gaiku_231204/tileset.json)
    - 建物モデル（3街区）：[https://assets.cms.plateau.reearth.io/assets/76/3ba1e2-0fbf-4acf-9c99-bd56c1743fdc/3gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/76/3ba1e2-0fbf-4acf-9c99-bd56c1743fdc/3gaiku_231204/tileset.json)
    - 建物モデル（4街区）：[https://assets.cms.plateau.reearth.io/assets/66/ec4e67-85b1-4605-bd77-2f0a013e4887/4gaiku_231204/tileset.json](https://assets.cms.plateau.reearth.io/assets/66/ec4e67-85b1-4605-bd77-2f0a013e4887/4gaiku_231204/tileset.json)
- 「マップエディター」左パネルの「レイヤー」新規作成アイコンをクリックし、「リソースからレイヤーを追加」をクリック

![](../resources/userMan/Untitled%2020.png)

- 表示されたレイヤー追加画面から「3D Tiles」を選択し、追加したい3D TilesのURLを入力して「レイヤー追加」をクリック

![](../resources/userMan/Untitled%2021.png)

- 追加したレイヤーの名前をダブルクリックして変更

![](../resources/userMan/Untitled%2022.png)

## エクスポートしたマーカー/インフォボックス（GeoJSON）の読み込み

- 「マップエディター」左パネルの「レイヤー」新規作成アイコンをクリックし、「リソースからレイヤーを追加」をクリック

![](../resources/userMan/Untitled%2023.png)

- 表示されたレイヤー追加画面から「Common」を選択。「ファイル形式」を「GeoJSON」、「ソースの種類」を「アセットから追加」にし、「アセット」の「アップロード」をクリック

![](../resources/userMan/Untitled%2024.png)

- 追加したいデータを選択し、アップロード

![](../resources/userMan/Untitled%2025.png)

- アップロードが完了したら、「レイヤー追加」をクリック

![](../resources/userMan/Untitled%2026.png)

- （任意）すでにアップロード済みのアセットから追加したい場合は、「アセット」の「選択」をクリック

![](../resources/userMan/Untitled%2027.png)

- （任意）表示されるアセット一覧から追加したいアセットをクリックし、「選択」をクリック

![](../resources/userMan/Untitled%2028.png)

# 8．レイヤーのスタイル編集

## スタイルの作成・記述

- マップエディターの中央下「レイヤースタイル」の＋ボタンをクリック

![](../resources/userMan/Untitled%2029.png)

- 作成したレイヤースタイルの名前を変更するには、名前部分をダブルクリック

![](../resources/userMan/Untitled%2030.png)

- 編集したいレイヤースタイルを選択した状態で右パネルに表示されるフィールドにスタイルのコードを記述し、「保存」をクリック

![](../resources/userMan/Untitled%2031.png)

## レイヤーへのスタイルの反映

- レイヤー一覧からスタイルを反映したいレイヤーをクリック
- 右パネルに表示されるアイコンから「スタイリング」のアイコンをクリック
- 右パネルに表示されるスタイル設定ボタンをクリック

![](../resources/userMan/Untitled%2032.png)

- 表示されたレイヤースタイル一覧から反映したいスタイルを選択し、「選択」をクリック

![](../resources/userMan/Untitled%2033.png)

