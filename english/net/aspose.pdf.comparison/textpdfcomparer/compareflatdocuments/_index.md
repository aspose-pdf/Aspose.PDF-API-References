---
title: "TextPdfComparer.CompareFlatDocuments"
linktitle: "CompareFlatDocuments"
articleTitle: "CompareFlatDocuments"
second_title: "Aspose.PDF for .NET"
description: "Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text."
type: docs
weight: 40
url: "/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/"
product_version: "26.9.0"
---
## CompareFlatDocuments([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/)) {#compareflatdocuments}

Compares two documents page by page.
 The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```csharp
public List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |

### Return Value

[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[DiffOperation](../../../aspose.pdf.comparison/diffoperation/)>

List of changes.

### See Also

* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/), string) {#compareflatdocuments_1}

Compares two documents page by page. The result is saved in a PDF file.
 The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```csharp
public List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |
| resultPdfDocumentPath | string | Path to the pdf file to save the comparison results. |

### Return Value

[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[DiffOperation](../../../aspose.pdf.comparison/diffoperation/)>

List of changes.

### See Also

* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

