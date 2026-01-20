---
title: Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare method
linktitle: Compare
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare method. Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## SideBySidePdfComparer::Compare(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::String, System::SharedPtr\<SideBySideComparisonOptions\>) method


Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```cpp
static void Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::String targetPdfPath, System::SharedPtr<SideBySideComparisonOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | The first document to compare. |
| document2 | System::SharedPtr\<Document\> | The second document to compare. |
| targetPdfPath | System::String | The path to PDF-file to save a comparison result. |
| options | System::SharedPtr\<SideBySideComparisonOptions\> | The comparison options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(System::SharedPtr\<Page\>, System::SharedPtr\<Page\>, System::String, System::SharedPtr\<SideBySideComparisonOptions\>) method


Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right.

```cpp
static void Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2, System::String targetPdfPath, System::SharedPtr<SideBySideComparisonOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | The first page to compare. |
| page2 | System::SharedPtr\<Page\> | The first page to compare. |
| targetPdfPath | System::String | The path to PDF-file to save a comparison result. |
| options | System::SharedPtr\<SideBySideComparisonOptions\> | The comparison options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
