---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer メソッド。ページをグラフィカルに比較します。比較結果は画像に配置されます。
type: docs
weight: 70
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage メソッド

ページをグラフィカルに比較します。比較結果は画像に配置されます。

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page1 | Page | 比較する最初のページ。 |
| page2 | Page | 比較する2番目のページ。 |
| resultImagePath | String | 対象画像ファイルのパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較されるページのサイズが異なる場合。resultImagePath が null または空の文字列の場合。保存する画像形式が不明な場合。 |

### 関連項目

* クラス [Page](../../../aspose.pdf/page/)
* クラス [GraphicalPdfComparer](../)
* 名前空間 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../../)