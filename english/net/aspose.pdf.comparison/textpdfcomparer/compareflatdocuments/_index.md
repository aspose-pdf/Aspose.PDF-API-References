---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer method. Compares two documents page by page. The documents are compared as a whole. Before comparing text the texts of document pages are combined into one text
type: docs
weight: 50
url: /net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

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

* class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Compares two documents page by page. The result is saved in a PDF file. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

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

* class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


