# Pistachio Gaming Valorant Map

ピスタチオゲーム部で使用するValorantの各マップ名称です。

基本的には一般的な名称を採用しています。

## 簡単な使い方

#### 1. Clone

```bash
$ git clone https://github.com/pistachiostudio/valorant_map.git
```

#### 2. base.pyを実行

- [Requests](https://requests.readthedocs.io/en/latest/)が必要です。pipもしくはRyeでインストールしてください。
- [API](https://dash.valorant-api.com/)から各マップの最新のベースマップを取得し、rawディレクトリに保存します。(上書きします)

```shell
$ python base.py
✔Downloaded ascent.png
✔Downloaded bind.png
✔Downloaded haven.png
✔Downloaded split.png
✔Downloaded icebox.png
✔Downloaded breeze.png
✔Downloaded fracture.png
✔Downloaded pearl.png
✔Downloaded lotus.png
✔Downloaded sunset.png
✔Downloaded abyss.png
- base map updated! -
```

#### 3. main.aiで好きにする

rawディレクトリのベース画像をそれぞれレイヤーごとでリンクしています。再リンクが必要な場合は適宜お願いします。

#### 4. レイヤーごとでにPNGを出力

Photoshopと違い、Illustratorにはレイヤーごとの書き出し機能がないので同封のスクリプト `export.jsx` を使用します。

- `Illustrator > ファイル > スクリプト > その他のスクリプト` から `export.jsx` を選択
- 書き出し先を選択。
- レイヤー(マップ)ごとに1500pxのPNGが出力されます。

## Fonts

- 左上のマップ名フォント: [https://www.dafont.com/valorant.font](https://www.dafont.com/valorant.font)
- エリア名のフォント: 源ノ角ゴシック (Heavy) [https://github.com/adobe-fonts/source-han-sans/blob/master/README-JP.md](https://github.com/adobe-fonts/source-han-sans/blob/master/README-JP.md)
  - Variable Fontではないものを使用しています

## なぜパスデータをやめたか

- 新しいマップが出てきたときにめんどくさい
- アプデが入るとめんどくさい
- 更新しなくてはというプレッシャーに押しつぶされた

## Mapの白データ

こちらの[API](https://dash.valorant-api.com/)から最新のものを拾います。[raw](https://github.com/pistachiostudio/valorant_map/tree/main/raw) ディレクトリに格納し、ベースとしてリンクします。これでとっても楽ちん。

- [Ascent](https://media.valorant-api.com/maps/7eaecc1b-4337-bbf6-6ab9-04b8f06b3319/displayicon.png)
- [Bind](https://media.valorant-api.com/maps/2c9d57ec-4431-9c5e-2939-8f9ef6dd5cba/displayicon.png)
- [Haven](https://media.valorant-api.com/maps/2bee0dc9-4ffe-519b-1cbd-7fbe763a6047/displayicon.png)
- [Split](https://media.valorant-api.com/maps/d960549e-485c-e861-8d71-aa9d1aed12a2/displayicon.png)
- [Icebox](https://media.valorant-api.com/maps/e2ad5c54-4114-a870-9641-8ea21279579a/displayicon.png)
- [Breeze](https://media.valorant-api.com/maps/2fb9a4fd-47b8-4e7d-a969-74b4046ebd53/displayicon.png)
- [Fracture](https://media.valorant-api.com/maps/b529448b-4d60-346e-e89e-00a4c527a405/displayicon.png)
- [Pearl](https://media.valorant-api.com/maps/fd267378-4d1d-484f-ff52-77821ed10dc2/displayicon.png)
- [Lotus](https://media.valorant-api.com/maps/2fe4ed3a-450a-948b-6d6b-e89a78e680a9/displayicon.png)
- [Sunset](https://media.valorant-api.com/maps/92584fbe-486a-b1b2-9faa-39b0f486b498/displayicon.png)
- [Abyss](https://media.valorant-api.com/maps/224b0a95-48b9-f703-1bd8-67aca101a61f/displayicon.png)


## Update

#### 2023.8.30

- パッチ8.11のAbyssの登場に対応

#### 2023.8.30

- パッチ7.04のSunsetの登場とBreezeのリワークに対応

#### 2023.6.21

- パッチ6.07のBindリワークに対応

#### 2023.1.11

- パッチ6.0のLotus登場とSplitリワークに対応

#### 2022.10.24

- パッチ5.0.8のFractureのリワークに対応

#### 2022.9.21

- パッチ5.0.6のPearlの修正に対応

#### 2022.7.6

- APIから一括で画像を取って来るbase.pyを追加

#### 2022.7.5

- 精神的にPearlに対応しきれずパスデータを潔く諦めた

#### 2022.3.8

- パッチノート4.0.3(ヨルのバフ、アストラナーフ他)のアイスボックスリワークにかなり適当に対応

#### 2022.1.11

- パッチノート4.0.1(ネオン登場)のブリーズとバインドのリワークに対応

## Samples

![Ascent](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/ascent.png)

![Bind](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/bind.png)

![Haven](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/haven.png)

![Split](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/split.png)

![Icebox](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/icebox.png)

![Breeze](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/breeze.png)

![Fracture](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/fracture.png)

![Pearl](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/pearl.png)

![Lotus](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/lotus.png)

![Sunset](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/sunset.png)

![Abyss](https://github.com/pistachiostudio/valorant_map/blob/main/for_thumbs/abyss.png)
