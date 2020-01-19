# Pokemon

## dataset

- https://www.kaggle.com/thedagger/pokemon-generation-one

## 参考モデル

- https://www.kaggle.com/trolukovich/predicting-pokemon-with-cnn-and-keras

## Fine Tuning

- https://pchun.work/resnet%E3%82%92fine-tuning%E3%81%97%E3%81%A6%E8%87%AA%E5%88%86%E3%81%8C%E7%94%A8%E6%84%8F%E3%81%97%E3%81%9F%E7%94%BB%E5%83%8F%E3%82%92%E5%AD%A6%E7%BF%92%E3%81%95%E3%81%9B%E3%82%8B/
- https://qiita.com/ha9kberry/items/daa2fc330c71485b2c27

## Batch Normarization 層を trainable = True にする

- https://qiita.com/mokoenator/items/6d7b8f670d3d1250d516

## Jupyter Notebook メモ

- pokemon.original.ipynb
  - https://www.kaggle.com/trolukovich/predicting-pokemon-with-cnn-and-keras と同じもの

- pokemon.ipynb
  - Xception モデル使用
  - 109層目から再学習
  - 入力画像ファイルサイズ： 128x128
  - 全結合層で GlobalAveragePooling2D を使用

- pokemon2.ipynb
  - Xception モデル使用
  - block12_sepconv1_act 層以降を再学習
  - 入力画像ファイルサイズ： 128x128
  - 全結合層で GlobalAveragePooling2D を使用

- pokemon3.ipynb
  - Xception モデル使用
  - block11_sepconv1_act 層以降を再学習
  - 入力画像ファイルサイズ： 128x128
  - 全結合層で GlobalAveragePooling2D を使用

- pokemon4.ipynb
  - Xception モデル使用
  - block14_sepconv1 層以降を再学習
  - 入力画像ファイルサイズ： 196x196
  - 全結合層で GlobalAveragePooling2D を使用

- pokemon5.ipynb
  - MobileNetV2 モデル使用
  - block_16_expand 層以降を再学習
  - 入力画像ファイルサイズ： 196x196
  - 全結合層で GlobalAveragePooling2D を使用

- pokemon6.ipynb
  - Xception モデル使用
  - すべての層を再学習
  - 入力画像ファイルサイズ： 196x196
  - 全結合層で GlobalAveragePooling2D を使用

- pokemon7.ipynb
  - Xception モデル使用
  - block14_sepconv1 層以降を再学習
  - 入力画像ファイルサイズ： 196x196
  - 全結合層で GlobalAveragePooling2D は使わずに Flatten を使用

- pokemon8.ipynb
  - Xception モデル使用
  - block14_sepconv1 層以降を再学習
  - 入力画像ファイルサイズ： 196x196
  - 全結合層で GlobalAveragePooling2D を使用
