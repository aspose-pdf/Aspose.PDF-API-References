---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "クラスは画像圧縮のオプションセットを含みます。"
type: docs
weight: 10
url: /ja/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

クラスは画像圧縮のオプションセットを含みます。

ImageCompressionOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| ImageCompressionOptions() | ImageCompressionOptions クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| compress_images | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。 |
| resize_images | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像がリサイズされます。 |
| image_quality | CompressIamges フラグが使用される際の画像圧縮レベルを指定します。 |
| max_resolution | 画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。 |
| version | 圧縮アルゴリズムのバージョン。可能な値は次のとおりです: 1. 標準圧縮、2. 高速（標準よりも高速な改良圧縮ですが、すべての画像に適用できない場合があります）、3. 混合（標準圧縮が高速アルゴリズムで圧縮できない画像に適用されます。これにより最高の圧縮が得られる可能性がありますが、"高速"アルゴリズムよりも遅くなります。"Fast" バージョンは画像のリサイズには適用できず（標準手法が使用されます）。デフォルトは "Standard" です。） |
| エンコーディング | 画像を保存する際に使用するエンコーディングを取得または設定します。 |

### 関連項目

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

