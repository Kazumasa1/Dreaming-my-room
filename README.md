# MY-ROOM-TOUR
デスクツアーやルームツアーの動画が好きなので、私の部屋も3Dモデルを用いて公開してみました <br>
https://kazumasa1.github.io/MY-ROOM-TOUR/
## Description
LiDARセンサーの付いたiPadを使い、自室を3DスキャンしてThree.jsでブラウザ上で見れるようにしました。<br>
#### 3Dスキャンに使用したもの
- iPad Pro（11インチ）（第2世代）
- 3d Scanner App


## DEMO
![MY-ROOM-TOUR](https://user-images.githubusercontent.com/70145199/153971702-514d0366-ccb1-4cc3-8652-cfa6dcacace6.png)

## Requirement
PCのブラウザで動作
### 注意！！！！！！！！
ブラウザの設定でハードウェアアクセラレーションを使用しないと動作が激おもになります

![chrome](https://user-images.githubusercontent.com/70145199/153993731-57b2993e-f880-44b4-8911-ddac413b2df6.png)

<font color="OrangeRed"></font>
## Usage
### 視点移動
周回軌道：左クリックでドラッグ<br>
水平移動：右クリックでドラッグ<br>
拡大・縮小：マウスホイール<br>

#### モデルの変更方法
65行のモデルのファイル名を変更したいモデルのファイル名に変更する（GLB形式のみ）<br>
※ファイルを格納するディレクトリに注意
```javascript
loader.load('models/MyRoomTour.glb', function(gltf) {
```
## Memo
今回使用した機材だと結構ガビガビな画質になってしまった。<br>
iPhone 13 Proとかだともっと綺麗にできるかも知れないです。<br>
