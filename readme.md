# 建設機械プレゼン資料

このリポジトリでは、建設機械の営業向けプレゼン資料を作成するための素材を管理しています。

## 内容
- `comparison.svg` : 自社と競合他社との性能比較を示すグラフ
- `create_presentation.py` : 上記グラフを取り込んだ PowerPoint (`machine_sales_pitch.pptx`) を生成するスクリプト

## 使い方
1. Python で [python-pptx](https://python-pptx.readthedocs.io/) をインストールします。
   ```bash
   pip install python-pptx
   ```
2. リポジトリ内でスクリプトを実行します。
   ```bash
   python3 create_presentation.py
   ```
3. `machine_sales_pitch.pptx` が生成されます。

スライド構成は次のとおりです。
1. タイトル
2. プレゼンの流れ
3. 他社との比較 (comparison.svg を使用)
4. まとめと次のステップ
