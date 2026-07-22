---
title: "Aspose::Pdf::LogicalStructure::StructureElement klass"
linktitle: "StructureElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LogicalStructure::StructureElement klass. Representerar en basklass för strukturelement i logisk struktur i C++."
type: docs
weight: 5500
url: /sv/cpp/aspose.pdf.logicalstructure/structureelement/
---
## StructureElement class


Representerar en basklass för strukturelement i logisk struktur.

```cpp
class StructureElement : public Aspose::Pdf::LogicalStructure::Element
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ChangeParentElement](./changeparentelement/)(const System::SharedPtr\<StructureElement\>\&, bool) | Ändra föräldraelement för aktuellt strukturelement. |
| [ClearId](./clearid/)() | Rensa ID för strukturelement. |
| [GenerateId](./generateid/)() | Generera ID för strukturelement. |
| [get_ActualText](./get_actualtext/)() | Hämtar den faktiska texten för strukturelement. |
| [get_AlternativeText](./get_alternativetext/)() | Hämtar den alternativa texten för strukturelement. |
| [get_Attributes](./get_attributes/)() const | Hämtar [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../) objekt. |
| [get_DefaultAttributeOwner](./get_defaultattributeowner/)() const | Hämtar [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../) objekt. |
| [get_ExpansionText](./get_expansiontext/)() | Hämtar expansionstexten för strukturelement. |
| [get_ID](./get_id/)() | Hämtar ID för strukturelement. |
| [get_Language](./get_language/)() | Hämtar språket för strukturelementet. |
| [get_Page](./get_page/)() | Hämtar sidan där vissa eller alla underordnade element kommer att renderas. |
| [get_StructureType](./get_structuretype/)() const | Hämtar typen av strukturelement. |
| [get_Title](./get_title/)() | Hämtar titeln för strukturelementet. |
| [Remove](./remove/)() | Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från underordnade objekt, det motsvarande objektet från dokumentet. |
| [RemoveAndMoveItsChildObjectsToItsParent](./removeandmoveitschildobjectstoitsparent/)(bool) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från underordnade objekt, och det motsvarande objektet från dokumentet. Infogar underordnade objekt från det borttagna objektet i dess tidigare förälders samling av underordnade objekt med start vid indexet för det borttagna objektet. |
| [set_ActualText](./set_actualtext/)(const System::String\&) | Ställer in den faktiska texten för strukturelementet. |
| [set_AlternativeText](./set_alternativetext/)(const System::String\&) | Ställer in den alternativa texten för strukturelementet. |
| [set_ExpansionText](./set_expansiontext/)(const System::String\&) | Ställer in expansionstexten för strukturelementet. |
| [set_Language](./set_language/)(const System::String\&) | Ställer in språket för strukturelementet. |
| [set_Title](./set_title/)(const System::String\&) | Ställer in titeln för strukturelementet. |
| [SetId](./setid/)(const System::String\&) | Ställer in ID för strukturelementet. |
| [SetTag](./settag/)(const System::String\&) | Ställer in anpassad tagg för strukturelementet. |
| [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) override | Bind ett strukturelement till innehållsströmmen BDC-operator. |
| [Tag](./tag/)(System::SharedPtr\<XForm\>) override | Bind ett strukturelement till innehållsströmmen [XForm](../../aspose.pdf/xform/). |
| [Tag](./tag/)(System::SharedPtr\<XImage\>) override | Bind ett strukturelement till [XImage](../../aspose.pdf/ximage/). |
| [Tag](./tag/)(System::SharedPtr\<Artifact\>) override | Bind ett strukturelement till [Artifact](../../aspose.pdf/artifact/). |
| [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) override | Bind ett strukturelement till Annotation. |
| [ToString](./tostring/)() const override | Returnerar en sträng som representerar det aktuella objektet. |
## Se även

* Class [Element](../element/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
