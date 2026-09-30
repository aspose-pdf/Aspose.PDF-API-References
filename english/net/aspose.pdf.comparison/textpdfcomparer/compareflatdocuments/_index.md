---
title: "TextPdfComparer.CompareFlatDocuments"
linktitle: "CompareFlatDocuments"
articleTitle: "CompareFlatDocuments"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextPdfComparer method. Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are co..."
type: docs
weight: 40
url: "/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/"
product_version: "26.9.0"
---
## CompareFlatDocuments([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/)) {#compareflatdocuments}

Compares two documents page by page.
 The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |

### Return Value

List of changes.

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/), string) {#compareflatdocuments_1}

Compares two documents page by page. The result is saved in a PDF file.
 The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | First document. |
| document2 | Document | Second document. |
| options | ComparisonOptions | Comparison options. |
| resultPdfDocumentPath | String | Path to the pdf file to save the comparison results. |

### Return Value

List of changes.

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../../aspose.pdf.comparison/comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

