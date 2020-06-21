# Blender Window Capture

![Screen](./screen.png)

Blender のウィンドウをキャプチャしてリアルタイムに画像に反映します。  
VR 機能使用時に手元が全くわからないと不便なので作成しました。  
速度上の問題でキャプチャ解像度は 256 \* 256 に制限されています。  
マルチウィンドウは考慮していません。

## Install

clone or download > Download ZIP から.zip ファイルを取得。  
Blender 上で 編集 > プリファレンス > アドオン > インストール から、.zip ファイルを選択しインストールする。  
インストール後、チェックボックスを有効にする。

## Usage

- 3D View > その他 > WindowCapture > start / end で開始・終了する。
- start すると `WindowCapture` という画像が生成され、リアルタイムにアップデートされる。
- 自分で Plane を作成しマテリアルを割り当て、シーンに配置する。カメラの子にすると便利。
