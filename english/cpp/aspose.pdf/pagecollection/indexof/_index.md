---
title: Aspose::Pdf::PageCollection::IndexOf method
linktitle: IndexOf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollection::IndexOf method. Returns index of the specified page in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf/pagecollection/indexof/
---
## PageCollection::IndexOf method


Returns index of the specified page.

```cpp
int32_t Aspose::Pdf::PageCollection::IndexOf(System::SharedPtr<Page> entity) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| entity | System::SharedPtr\<Page\> | [Page](../../page/) object. Pages numbers start from 1. |

### ReturnValue

Index of the page in collection.
## Remarks


Pages numbers start from 1. Returns 0 in case collection doesn't contain the page. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
