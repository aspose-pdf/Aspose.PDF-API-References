---
title: Aspose::Pdf::DocumentExtensions::SplitSharedImages method
linktitle: SplitSharedImages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocumentExtensions::SplitSharedImages method. For Images in Resources if two pages checks for common XImages and for similar cases splits them, by creating duplicate XImages in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/documentextensions/splitsharedimages/
---
## DocumentExtensions::SplitSharedImages method


For Images in [Resources](../../resources/) if two pages checks for common XImages and for similar cases splits them, by creating duplicate XImages.

```cpp
static void Aspose::Pdf::DocumentExtensions::SplitSharedImages(System::SharedPtr<Document> doc, System::SharedPtr<Page> page_1, System::SharedPtr<Page> page_2)
```


| Parameter | Type | Description |
| --- | --- | --- |
| doc | System::SharedPtr\<Document\> | The document containing both collections. |
| page_1 | System::SharedPtr\<Page\> | First page for compare. |
| page_2 | System::SharedPtr\<Page\> | Second page for compare/ |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Page](../../page/)
* Class [DocumentExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
