---
title: "SideBySidePdfComparer.Compare"
linktitle: "Compare"
articleTitle: "Compare"
second_title: "Aspose.PDF for .NET"
description: "Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second. You can open it in Adobe Acrobat in ..."
type: docs
weight: 10
url: "/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/"
product_version: "26.9.0"
---
## Compare([Page](../../../aspose.pdf/page/), [Page](../../../aspose.pdf/page/), string, [SideBySideComparisonOptions](../../../aspose.pdf.comparison/sidebysidecomparisonoptions/)) {#compare}

Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second.
 You can open it in Adobe Acrobat in Two-page view to see the changes side by side.
 Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```csharp
public SideBySidePagesComparisonResult Compare(Page page1, Page page2, string targetPdfPath, SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page to compare. |
| page2 | Page | The first page to compare. |
| targetPdfPath | string | The path to PDF-file to save a comparison result. |
| options | SideBySideComparisonOptions | The comparison options. |

### Return Value

[SideBySidePagesComparisonResult](../../../aspose.pdf.comparison/sidebysidepagescomparisonresult/)

The comparison result.

### See Also

* class [SideBySidePagesComparisonResult](../../../aspose.pdf.comparison/sidebysidepagescomparisonresult/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), string, [SideBySideComparisonOptions](../../../aspose.pdf.comparison/sidebysidecomparisonoptions/)) {#compare_1}

Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document.
 First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc.
 You can open it in Adobe Acrobat in Two-page view to see the changes side by side.
 Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```csharp
public SideBySideDocsComparisonResult Compare(Document document1, Document document2, string targetPdfPath, SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | The first document to compare. |
| document2 | Document | The second document to compare. |
| targetPdfPath | string | The path to PDF-file to save a comparison result. |
| options | SideBySideComparisonOptions | The comparison options. |

### Return Value

[SideBySideDocsComparisonResult](../../../aspose.pdf.comparison/sidebysidedocscomparisonresult/)

The comparison result.

### See Also

* class [SideBySideDocsComparisonResult](../../../aspose.pdf.comparison/sidebysidedocscomparisonresult/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare([Page](../../../aspose.pdf/page/), [Page](../../../aspose.pdf/page/), Stream, [SideBySideComparisonOptions](../../../aspose.pdf.comparison/sidebysidecomparisonoptions/)) {#compare_2}

Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second.
 You can open it in Adobe Acrobat in Two-page view to see the changes side by side.
 Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```csharp
public SideBySidePagesComparisonResult Compare(Page page1, Page page2, Stream targetStream, SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | The first page to compare. |
| page2 | Page | The first page to compare. |
| targetStream | Stream | The target stream to save a comparison result. |
| options | SideBySideComparisonOptions | The comparison options. |

### Return Value

[SideBySidePagesComparisonResult](../../../aspose.pdf.comparison/sidebysidepagescomparisonresult/)

The comparison result.

### See Also

* class [SideBySidePagesComparisonResult](../../../aspose.pdf.comparison/sidebysidepagescomparisonresult/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare([Document](../../../aspose.pdf/document/), [Document](../../../aspose.pdf/document/), Stream, [SideBySideComparisonOptions](../../../aspose.pdf.comparison/sidebysidecomparisonoptions/)) {#compare_3}

Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document.
 First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc.
 You can open it in Adobe Acrobat in Two-page view to see the changes side by side.
 Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```csharp
public SideBySideDocsComparisonResult Compare(Document document1, Document document2, Stream targetStream, SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | The first document to compare. |
| document2 | Document | The second document to compare. |
| targetStream | Stream | The target stream to save a comparison result. |
| options | SideBySideComparisonOptions | The comparison options. |

### Return Value

[SideBySideDocsComparisonResult](../../../aspose.pdf.comparison/sidebysidedocscomparisonresult/)

The comparison result.

### See Also

* class [SideBySideDocsComparisonResult](../../../aspose.pdf.comparison/sidebysidedocscomparisonresult/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

