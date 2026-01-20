---
title: Aspose::Pdf::LogicalStructure::ElementList::Item method
linktitle: Item
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::ElementList::Item method. Retrieves a element at the given index in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.logicalstructure/elementlist/item/
---
## ElementList::Item method


Retrieves a element at the given index.

```cpp
virtual System::SharedPtr<Element> Aspose::Pdf::LogicalStructure::ElementList::Item(int32_t index)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index into the list of elements. |

### ReturnValue

The [T:/Aspose::Pdf::LogicalStructure::Element](../) with the specified index in the collection. If *index*  is greater than or equal to the number of elements in the list, this returns null.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Element](../../element/)
* Class [ElementList](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
