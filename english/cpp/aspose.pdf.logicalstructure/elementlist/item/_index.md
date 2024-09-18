---
title: Aspose::Pdf::LogicalStructure::ElementList::Item method
linktitle: Item
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::ElementList::Item method. Retrieves a element at the given index in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.logicalstructure/elementlist/item/
---
## ElementList::Item method


Retrieves a element at the given index.

```cpp
virtual ASPOSE_PDF_SHARED_API System::SharedPtr<Element> Aspose::Pdf::LogicalStructure::ElementList::Item(int32_t index)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index into the list of elements. |

### ReturnValue

The [T:/Aspose::Pdf::LogicalStructure::Element](../) with the specified index in the collection. If *index*  is greater than or equal to the number of elements in the list, this returns null.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The index into the list of elements.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Element](../../element/)
* Class [ElementList](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
