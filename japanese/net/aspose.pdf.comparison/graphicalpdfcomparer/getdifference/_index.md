---
title: GraphicalPdfComparer.GetDifference
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer メソッド。ページ画像間の違いを取得します。結果には比較された最初のページの画像と違いの配列が含まれます。
type: docs
weight: 90
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/getdifference/
---
## GraphicalPdfComparer.GetDifference メソッド

ページ画像間の違いを取得します。結果には比較された最初のページの画像と違いの配列が含まれます。

```csharp
public ImagesDifference GetDifference(Page page1, Page page2)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page1 | Page | 最初のページ。 |
| page2 | Page | 2 番目のページ。 |

### 戻り値

[`ImagesDifference`](../../imagesdifference/) インスタンス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較されるページのサイズが異なる場合。 |

### 参照

* クラス [ImagesDifference](../../imagesdifference/)
* クラス [Page](../../../aspose.pdf/page/)
* クラス [GraphicalPdfComparer](../)
* 名前空間 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../../)