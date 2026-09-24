---
title: "TextPdfComparer.CompareDocumentsPageByPage"
linktitle: "CompareDocumentsPageByPage"
articleTitle: "CompareDocumentsPageByPage"
second_title: "Aspose.PDF for .NET"
description: "Compares two documents page by page."
type: docs
weight: 20
url: "/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/"
product_version: "26.9.0"
---
## CompareDocumentsPageByPage([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/)) {#comparedocumentspagebypage}

Compares two documents page by page.

```csharp
public List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, Document document2, ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document.. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |

### Return Value

[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[DiffOperation](../../../aspose.pdf.comparison/diffoperation/)>>

List of changes by page.

### See Also

* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/), string) {#comparedocumentspagebypage_1}

Compares two documents page by page. The result is saved in a PDF file.

```csharp
public List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document.. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |
| resultPdfDocumentPath | string | Path to the pdf file to save the comparison results. |

### Return Value

[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[DiffOperation](../../../aspose.pdf.comparison/diffoperation/)>>

List of changes by page.

### See Also

* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

