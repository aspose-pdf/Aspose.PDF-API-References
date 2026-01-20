---
title: Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage method
linktitle: CompareDocumentsPageByPage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage method. Compares two documents page by page in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## TextPdfComparer::CompareDocumentsPageByPage(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::SharedPtr\<ComparisonOptions\>) method


Compares two documents page by page.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::SharedPtr<ComparisonOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | First document.. |
| document2 | System::SharedPtr\<Document\> | Second document. |
| options | System::SharedPtr\<ComparisonOptions\> | [Comparison](../../) options. |

### ReturnValue

List of changes by page.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareDocumentsPageByPage(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::SharedPtr\<ComparisonOptions\>, System::String) method


Compares two documents page by page. The result is saved in a PDF file.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::SharedPtr<ComparisonOptions> options, System::String resultPdfDocumentPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | First document.. |
| document2 | System::SharedPtr\<Document\> | Second document. |
| options | System::SharedPtr\<ComparisonOptions\> | [Comparison](../../) options. |
| resultPdfDocumentPath | System::String | Path to the pdf file to save the comparison results. |

### ReturnValue

List of changes by page.

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
