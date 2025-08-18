[Back/戻る](https://github.com/Sanka1610/RVX-anddea)


# RVX anddea

anddea氏によるReVancedパッチを適用した、モジュールおよびパッチ済みAPKを提供します。

ビルドは[GitHub Actions](https://github.com/Sanka1610/RVX-anddea/actions/workflows/build.yml)によって自動生成されています。


## サポート対象

### 対応アプリ

YouTube、YouTube Music

### YouTube

- #### 対応アーキテクチャ

arm64-v8a、armabi-v7a、x86、x64

- #### 対応バージョン

v19.47.53、v20.12.46

※v20.12.46は、YouTube v20.xがプリインストールされている端末向けに提供しています。不安定な場合があるため使用には注意してください。

- #### root環境

Magisk系列、KernelSU系列、APatch系列

### YouTube Music

- #### 対応アーキテクチャ

arm64-v8a

- #### 対応バージョン

v8.12.53

- #### root環境

Magisk系列、KernelSU系列、APatch系列



## サポート対象

  - ### 対応アプリ

    - #### YouTube

      - 対応アーキテクチャ : arm64-v8a、armeabi-v7a、x86、x64

      - 対応バージョン : v19.47.53、v20.12.46

        - ※v20.12.46は、YouTube v20.xがプリインストールされている端末向けに提供しています。不安定な場合があるため使用には注意してください。

      - root環境 : Magisk系列、KernelSU系列、APatch系列

    - #### YouTube Music

      - 対応アーキテクチャ : arm64-v8a

      - 対応バージョン : v8.12.53

      - root環境 : Magisk系列、KernelSU系列、APatch系列


## ダウンロード

最新のリリースは[こちら](https://github.com/Sanka1610/RVX-anddea/releases/)から入手できます。

モジュールかパッチ済みAPKを選択して使用してください。


## 使用上の注意

### root環境

- Zygisk、またはその代替によって動作します。

  ※Zygisk Assistantを利用する場合は、Youtube、Youtube MusicにSU権限を与える必要があります。

- PlayStoreによる自動更新を無効化するために、[zygisk-detach](https://github.com/j-hc/zygisk-detach)の利用を推奨します。

### 非root環境

- [MicroG/GmsCore](https://github.com/microg/GmsCore)、またはその代替によって動作します。

- 元のYoutubeアプリとは別のアプリとしてインストールされます。


## クレジット

### [**j-hc**](https://github.com/j-hc)

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)の公開テンプレート

### [**anddea**](https://github.com/anddea)

[ReVanced Patches](https://github.com/anddea/revanced-patches)

