# [Global Wheat Detection](https://www.kaggle.com/c/global-wheat-detection)
## Can you help identify wheat heads using image analysis?
---
## これは何か
- Global Wheat Detectionにて使用したコード類をまとめました。
- 自分のソリューションや反省点については、`./反省.md`に記載しております。

## コンペ概要
- ヨーロッパの小麦画像をもとに、オーストラリア、日本、中国の小麦画像の物体検知を行う。
- クラス数: 1(小麦)

## 使用したノートブック
- ./notebook/EDA.ipynb # Augmentation調査及びラベル修正
- ./notebook/effdet.ipynb # 学習用
- ./notebook/inference_efficientdet_tta_pl.ipynb # 推論用
- colabで動かす前提のノートブックのため、序盤にgoogle drive マウントの処理が記載されています。

## データ
- [こちらから](https://www.kaggle.com/c/global-wheat-detection/data)
- 規約に同意する必要あり

## モデル
- EfficientDet: [こちらから](https://www.kaggle.com/mathurinache/efficientdet)ダウンロードしてください。

## 結果
- まだ結果待ちだが、ライセンス違反で上位が弾かれてもメダルは厳しそうです。
