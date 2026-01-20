---
title: Aspose::Pdf::LogicalStructure::ElementListImplementation::Item method
linktitle: Item
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::ElementListImplementation::Item method. Retrieves a element at the given index in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.logicalstructure/elementlistimplementation/item/
---
## ElementListImplementation::Item method


Retrieves a element at the given index.

```cpp
System::SharedPtr<Element> Aspose::Pdf::LogicalStructure::ElementListImplementation::Item(int32_t index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index into the list of elements. |

### ReturnValue

The [T:/Aspose::Pdf::LogicalStructure::Element](../) with the specified index in the collection. If *index*  is greater than or equal to the number of elements in the list, this returns null.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Element](../../element/)
* Class [ElementListImplementation](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
