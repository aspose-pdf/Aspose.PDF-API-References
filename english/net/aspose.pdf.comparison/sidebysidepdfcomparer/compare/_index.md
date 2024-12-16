---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer method. Compares two pages. The result is saved in a PDF document in which the first page is written first and then the second. You can open it in Adobe Acrobat in Twopage view to see the changes side by side. Deletions are noted on the page on the left and insertions are noted on the page on the right
type: docs
weight: 10
url: /net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page to compare. |
| page2 | Page | The first page to compare. |
| targetPdfPath | String | The path to PDF-file to save a comparison result. |
| options | SideBySideComparisonOptions | The comparison options. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | The first document to compare. |
| document2 | Document | The second document to compare. |
| targetPdfPath | String | The path to PDF-file to save a comparison result. |
| options | SideBySideComparisonOptions | The comparison options. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


