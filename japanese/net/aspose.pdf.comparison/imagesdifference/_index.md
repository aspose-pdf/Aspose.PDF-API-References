---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ImagesDifference クラス。2つの PDF ページを比較した結果のクラスを表します。
type: docs
weight: 3230
url: /ja/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference クラス

2つの PDF ページを比較した結果のクラスを表します。

```csharp
public sealed class ImagesDifference : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | 差分配列を取得します。この配列は、LockBits メソッドの結果として得られる元の画像データ配列に似ています。 |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | 差分の高さ。 |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | 比較された最初のページの画像を取得します。画像のピクセル形式は 24bpp です。 |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | 差分画像データのストライド。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | 指定された色を使用して差分配列をビットマップ画像に変換します。 |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | オブジェクトが破棄される前に必要なクリーンアップ操作を実行します。 |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | 差分配列をソース画像に適用して、宛先画像を表す新しいビットマップを返します。 |

### 参照

* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)