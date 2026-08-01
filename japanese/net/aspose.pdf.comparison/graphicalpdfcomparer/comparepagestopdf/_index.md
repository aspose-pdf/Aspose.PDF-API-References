---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "GraphicalPdfComparer メソッド。ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。"
type: docs
weight: 80
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| page1 | ページ | 最初のページです。 |
| page2 | ページ | 2番目のページです。 |
| resultPdfPath | String | 対象 PDF ファイルへのパスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較対象のページサイズが異なる場合。resultPdfPath が null または空文字列の場合。 |

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| page1 | ページ | 最初のページです。 |
| page2 | ページ | 2番目のページです。 |
| pdfDocument | Document | PDF ドキュメントのインスタンスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較対象のページのサイズが異なる場合。 |

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


