---
title: "TextPdfComparer Class"
linktitle: "TextPdfComparer"
articleTitle: "TextPdfComparer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.TextPdfComparer class. Represents a class to comparison two PDF pages or PDF documents."
type: docs
weight: 230
url: "/net/aspose.pdf.comparison/textpdfcomparer/"
keywords: "TextPdfComparer, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextPdfComparer class

Represents a class to comparison two PDF pages or PDF documents.

```csharp
public class TextPdfComparer
```

## Constructors

| Name | Description |
| --- | --- |
| [TextPdfComparer](./textpdfcomparer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| static [AssemblyDestinationPageText](./assemblydestinationpagetext/)(List<DiffOperation>) | Restores changed text from the list of changes. |
| static [AssemblySourcePageText](./assemblysourcepagetext/)(List<DiffOperation>) | Restores the original text from the list of changes. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(Document, Document, ComparisonOptions) | Compares two documents page by page. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(Document, Document, ComparisonOptions, string) | Compares two documents page by page. The result is saved in a PDF file. |
| static [CompareFlatDocuments](./compareflatdocuments/)(Document, Document, ComparisonOptions) | Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text. |
| static [CompareFlatDocuments](./compareflatdocuments/)(Document, Document, ComparisonOptions, string) | Compares two documents page by page. The result is saved in a PDF file. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text. |
| static [ComparePages](./comparepages/)(Page, Page, ComparisonOptions) | Compares document pages. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(List<DiffOperation>) | Gets comparison statistics. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(List<List<DiffOperation>>) | Gets documents comparison statistics. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

