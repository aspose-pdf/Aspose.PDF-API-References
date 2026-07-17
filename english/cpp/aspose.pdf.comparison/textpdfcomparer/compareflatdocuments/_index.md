---
title: Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments method
linktitle: CompareFlatDocuments
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments method. Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## TextPdfComparer::CompareFlatDocuments(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) method


Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | First document. |
| document2 | const System::SharedPtr\<Document\>\& | Second document. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) options. |

### ReturnValue

List of changes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareFlatDocuments(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) method


Compares two documents page by page. The result is saved in a PDF file. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options, const System::String &resultPdfDocumentPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | First document. |
| document2 | const System::SharedPtr\<Document\>\& | Second document. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Comparison](../../) options. |
| resultPdfDocumentPath | const System::String\& | Path to the pdf file to save the comparison results. |

### ReturnValue

List of changes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [String](../../../system/string/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
