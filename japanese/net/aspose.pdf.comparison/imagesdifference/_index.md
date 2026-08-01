---
title: "クラス ImagesDifference"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Comparison.ImagesDifference クラス。2つの PDF ページを比較した結果クラスを表します。"
type: docs
weight: 3340
url: /ja/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

2 つの PDF ページを比較した結果クラスを表します。

```csharp
public sealed class ImagesDifference : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | 差分配列を取得します。この配列は LockBits メソッドの結果として取得された元の画像データ配列に似ています。 |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | 差分の高さです。 |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | 最初に比較されたページの画像を取得します。画像のピクセル形式は 24bpp です。 |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | 差分画像データのストライドです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | 指定された色を使用して差分配列をビットマップ画像に変換します。 |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | オブジェクトが破棄される前に、必要なクリーンアップ操作を実行します。 |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | 差分配列をソース画像に適用して、宛先画像を表す新しいビットマップを返します。 |

### 関連項目

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


