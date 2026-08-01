---
title: "クラス ImageCompressionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions クラス。クラスは画像圧縮のための設定オプションを含んでいます。"
type: docs
weight: 8090
url: /ja/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

クラスは画像圧縮のオプションセットを含みます。

```csharp
public class ImageCompressionOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | このフラグが true に設定されている場合、ドキュメント内の画像は圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。 |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | 画像を保存する際に使用するエンコーディングを取得または設定します。 |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | CompressImages フラグが使用されている場合の画像圧縮レベルを指定します。 |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | 画像の最大解像度を指定します。画像の解像度がこれより高い場合、スケーリングされます。 |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像はリサイズされます。 |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | 圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. standard compression、2. fast（標準より高速な改良圧縮ですが、すべての画像に適用できるわけではありません）、3. mixed（高速アルゴリズムで圧縮できない画像に標準圧縮が適用されます。これにより最高の圧縮が得られる可能性がありますが、"fast" アルゴリズムより遅くなります。バージョン "Fast" は画像のリサイズには適用できず（標準手法が使用されます）。デフォルトは "Standard" です。 |

### 関連項目

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


