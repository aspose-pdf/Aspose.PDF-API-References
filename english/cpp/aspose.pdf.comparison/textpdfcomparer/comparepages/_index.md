---
title: Aspose::Pdf::Comparison::TextPdfComparer::ComparePages method
linktitle: ComparePages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer::ComparePages method. Compares document pages in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.comparison/textpdfcomparer/comparepages/
---
## TextPdfComparer::ComparePages method


Compares document pages.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::ComparePages(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2, System::SharedPtr<ComparisonOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | First page. |
| page2 | System::SharedPtr\<Page\> | Second page. |
| options | System::SharedPtr\<ComparisonOptions\> | [Comparison](../../) options. |

### ReturnValue

The list of changes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
