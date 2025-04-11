---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer メソッド。文書をグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。
type: docs
weight: 60
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## GraphicalPdfComparer.CompareDocumentsToPdf メソッド

文書をグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document1 | Document | 比較する最初の文書。 |
| document2 | Document | 比較する2番目の文書。 |
| resultPdfPath | String | 目標の PDF ファイルパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較されるページのサイズが異なる場合。resultPdfPath が null または空の文字列の場合。 |

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [GraphicalPdfComparer](../)
* 名前空間 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../../)