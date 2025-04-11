---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions クラス。クラスは画像圧縮のためのオプションを含みます。
type: docs
weight: 7950
url: /ja/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions クラス

クラスは画像圧縮のためのオプションを含みます。

```csharp
public class ImageCompressionOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。 |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | 画像を保存するために使用されるエンコーディングを取得または設定します。 |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | CompressIamges フラグが使用されるときの画像圧縮のレベルを指定します。 |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | 画像の最大解像度を指定します。画像がより高い解像度を持っている場合、それはスケーリングされます。 |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | このフラグが true に設定され、CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きい場合、画像がリサイズされます。 |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | 圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. 標準圧縮、2. 高速（標準よりも速いが、すべての画像に適用できない場合がある改善された圧縮）、3. 混合（高速アルゴリズムで圧縮できない画像には標準圧縮が適用され、これにより最良の圧縮が得られますが、「高速」アルゴリズムよりも遅くなります。「高速」バージョンは画像のリサイズには適用されず（標準メソッドが使用されます）。デフォルトは「標準」です。 |

### 参照

* 名前空間 [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* アセンブリ [Aspose.PDF](../../)