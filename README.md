# Menhera-chan-classification

An Simple CNN classifier for verifying a given Menhera-chan(七瀬くるみ/メンヘラちゃん) sticker is super deformer(スーパー・デフォルメ) or not.

Menhera-chan sticker:

https://store.line.me/stickershop/product/1862778/ja

## summary

Useing Pytorch.

Extend each stickers to 512x512.

Random select 25% stickers each class into validating data.

Rotate, flip, no clip.

Train/valid accuracy unstable in train process(50 epochs), both hit 95%+ best.