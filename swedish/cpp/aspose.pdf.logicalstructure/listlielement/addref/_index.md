---
title: "Aspose::Pdf::LogicalStructure::ListLIElement::AddRef metod"
linktitle: "AddRef"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::ListLIElement::AddRef metod. Lägger till en referens till det angivna StructureElement inom detta Table of Contents Item (TOCI) element. Detta används vanligtvis när ListLIElement fungerar som en TOC‑rubrik i nästlade innehållsförteckningar i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.logicalstructure/listlielement/addref/
---
## ListLIElement::AddRef method


Lägger till en referens till det angivna [StructureElement](../../structureelement/) inom detta [Table](../../../aspose.pdf/table/) för innehållsförteckningselement (TOCI). Detta används vanligtvis när **[ListLIElement](../)** fungerar som en TOC‑rubrik i nästlade innehållsförteckningar.

```cpp
void Aspose::Pdf::LogicalStructure::ListLIElement::AddRef(const System::SharedPtr<StructureElement> &referencedStructureElement)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| referencedStructureElement | const System::SharedPtr\<StructureElement\>\& | Det [StructureElement](../../structureelement/) som ska refereras av detta TOCI-element. |
## Anmärkningar



Att associera ett strukturelement, såsom en rubrik eller en annan innehållssektion, med ett TOCI-element säkerställer korrekt logisk struktur och förbättrar navigeringsbeteendet i taggade PDF-filer.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [ListLIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
