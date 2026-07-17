---
title: Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare method
linktitle: Compare
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare method. Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | The first document to compare. |
| document2 | const System::SharedPtr\<Document\>\& | The second document to compare. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | The target stream to save a comparison result. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | The comparison options. |

### ReturnValue

The comparison result.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | The first document to compare. |
| document2 | const System::SharedPtr\<Document\>\& | The second document to compare. |
| targetPdfPath | const System::String\& | The path to PDF-file to save a comparison result. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | The comparison options. |

### ReturnValue

The comparison result.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | The first page to compare. |
| page2 | const System::SharedPtr\<Page\>\& | The first page to compare. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | The target stream to save a comparison result. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | The comparison options. |

### ReturnValue

The comparison result.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | The first page to compare. |
| page2 | const System::SharedPtr\<Page\>\& | The first page to compare. |
| targetPdfPath | const System::String\& | The path to PDF-file to save a comparison result. |
| options | const System::SharedPtr\<SideBySideComparisonOptions\>\& | The comparison options. |

### ReturnValue

The comparison result.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
