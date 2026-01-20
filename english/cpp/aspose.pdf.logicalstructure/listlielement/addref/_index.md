---
title: Aspose::Pdf::LogicalStructure::ListLIElement::AddRef method
linktitle: AddRef
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::ListLIElement::AddRef method. Adds a reference to the specified StructureElement within this Table of Contents Item (TOCI) element. This is typically used when ListLIElement serves as a TOC header in nested tables of contents in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.logicalstructure/listlielement/addref/
---
## ListLIElement::AddRef method


Adds a reference to the specified [StructureElement](../../structureelement/) within this [Table](../../../aspose.pdf/table/) of Contents Item (TOCI) element. This is typically used when **[ListLIElement](../)** serves as a TOC header in nested tables of contents.

```cpp
void Aspose::Pdf::LogicalStructure::ListLIElement::AddRef(System::SharedPtr<StructureElement> referencedStructureElement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| referencedStructureElement | System::SharedPtr\<StructureElement\> | The [StructureElement](../../structureelement/) to be referenced by this TOCI element. |
## Remarks



Associating a structure element, such as a header or another content section, with a TOCI element ensures correct logical structure and improves navigational behavior in tagged PDFs. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [ListLIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
