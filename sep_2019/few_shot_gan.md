---
title:  Few-Shot Adversarial Learning of Realistic Neural Talking Head Models
date:   2019-09-11-15
categories: CV
duration: 60min
---

## 1. どんなもの？

顔の動画生成を少ない画像（一枚）のみのデータセットで生成することができるという論文

## 2. 先行研究と比べてどこがすごいの？

従来の動画生成には、学習させたい対象の大量の画像が必要だったが、今回のアーキテクチャと事前学習によって、対象の画像を少ない枚数で学習できるようになった。

## 3. 技術や手法の"キモ"はどこにある？

Text-to-speechのfew-shotの研究を画像生成GANに適用し、メタラーニングでプログレスを出したシステム２つを組み込んだこと

## 4. どうやって有効だと検証した？

先行研究のスコアとFIDで比較、オリジナル画像とface recognitionシステムで顔の特徴が崩れてないかCCIMで比較、人による生成画像判定

## 5. 議論はあるか？

視線の生成はできない、体から下は顔と同時に出来るような十分な統計モデルがないから難しい

## 6. 不明点・わからないところ・コメント

## 7. 次に読むべき論文はあるか？

構成されてる論文

### 論文情報・リンク

- [Egor Zakharov, Aliaksandra Shysheya, Egor Burkov, Victor Lempitsky，"Few-Shot Adversarial Learning of Realistic Neural Talking Head Models，" ジャーナル名，voluem，no.，ページ，年](https://arxiv.org/pdf/1905.08233.pdf)
