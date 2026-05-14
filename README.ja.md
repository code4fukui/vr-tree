# vr-tree

A-Frameで構築された、ボクセルベースの木を手続き的に生成し、インタラクティブに操作できるシンプルなVR環境です。

## デモ

https://code4fukui.github.io/vr-tree/

![グリッド平面上に、手続き的に生成された2つのボクセル木を表示するVRシーン。1つの木は背が高く角ばっており、もう1つは背が低く丸みを帯びている。前景にはVRコントローラーが見える。](https://user-images.githubusercontent.com/1715217/199850195-94a52e5e-3fb5-4af7-9fce-14697eaac39f.png)

## 機能

- [voxel-trees](https://github.com/code4fukui/voxel-trees) を使用した手続き的な木の生成。
- 2つの異なる生成アルゴリズム: `"subspace"`（角ばった形状）と `"guybrush"`（丸みを帯びた形状）。
- ブロックを配置・削除できるインタラクティブなVRワールド。
- Oculus Touchコントローラーをサポートし、4種類のブロック（土、乾いた木、葉、草）を操作可能。

## はじめに

### 前提条件

- コントローラー付きのVRヘッドセット（例: Oculus Quest/Rift）。
- WebXR対応ブラウザ（例: Oculus Browser, Firefox Reality）。

### ローカルでの実行

1. リポジトリをクローンします:
    ```sh
    git clone https://github.com/code4fukui/vr-tree.git
    ```
2. プロジェクトディレクトリに移動します:
    ```sh
    cd vr-tree
    ```
3. ローカルWebサーバーを起動します。例えばPythonを使用する場合:
    ```sh
    python -m http.server
    ```
4. ブラウザで `http://localhost:8000` にアクセスします。
