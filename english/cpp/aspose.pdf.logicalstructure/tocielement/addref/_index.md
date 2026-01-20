---
title: Aspose::Pdf::LogicalStructure::TOCIElement::AddRef method
linktitle: AddRef
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::TOCIElement::AddRef method. Adds a reference to the specified structure element within the Table of Contents Item (TOCI) element in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.logicalstructure/tocielement/addref/
---
## TOCIElement::AddRef method


Adds a reference to the specified structure element within the [Table](../../../aspose.pdf/table/) of Contents Item (TOCI) element.

```cpp
void Aspose::Pdf::LogicalStructure::TOCIElement::AddRef(System::SharedPtr<StructureElement> referencedStructureElement)
```


| Parameter | Type | Description |
| --- | --- | --- |
| referencedStructureElement | System::SharedPtr\<StructureElement\> | The [StructureElement](../../structureelement/) to be referenced by this TOCI element. |
## Remarks



Associating a structure element, such as a header or another content section, with a TOCI element ensures correct logical structure and improves navigational behavior in tagged PDFs. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [TOCIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
