---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer メソッド。ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。
type: docs
weight: 80
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page1 | Page | 最初のページ。 |
| page2 | Page | 2 番目のページ。 |
| resultPdfPath | String | 対象の PDF ファイルへのパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較されるページのサイズが異なる場合。resultPdfPath が null または空の文字列の場合。 |

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [GraphicalPdfComparer](../)
* 名前空間 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page1 | Page | 最初のページ。 |
| page2 | Page | 2 番目のページ。 |
| pdfDocument | Document | PDF ドキュメントインスタンス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較されるページのサイズが異なる場合。 |

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [GraphicalPdfComparer](../)
* 名前空間 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../../)