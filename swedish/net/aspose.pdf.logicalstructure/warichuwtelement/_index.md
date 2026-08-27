---
title: "Klass WarichuWTElement"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LogicalStructure.WarichuWTElement klass. Representerar WT struktur-element i den logiska strukturen för Warichu"
type: docs
weight: 7030
url: /sv/net/aspose.pdf.logicalstructure/warichuwtelement/
---
## WarichuWTElement class

Representerar WT-strukturelement i den logiska strukturen för Warichu.

```csharp
public sealed class WarichuWTElement : WarichuChildElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Hämtar eller anger den faktiska texten för strukturelementet. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Hämtar eller anger den alternativa texten för strukturelementet. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Hämtar StructureAttributeCollection‑objektet. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar samlingen av barn‑Element‑objekt. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Hämtar AttributeOwnerStandard‑objektet. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Hämtar eller anger expansions‑texten för strukturelementet. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Hämtar ID‑t för strukturelementet. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Hämtar eller anger språket för strukturelementet. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Hämtar sidan där vissa eller alla barn‑element kommer att renderas. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämta föräldraelementet. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Hämtar typen av strukturelement. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Hämtar eller anger titeln för strukturelementet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägg till Element i samlingen av barn. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändra föräldraelement för aktuellt strukturelement |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensa alla barn. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Rensa ID för strukturelementet. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hitta element av en given typ |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generera ID för strukturelementet. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infoga element i samling av barn på angivet index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, det motsvarande objektet från dokumentet. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt och det motsvarande objektet från dokumentet. Infogar barnobjekt från det borttagna objektet i dess tidigare förälders barnobjektssamling med start vid indexet för det borttagna objektet. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Ta bort barn vid. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Ställer in ID för strukturelementet. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Ställer in anpassad tagg för strukturelementet. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Koppla ett strukturelement till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Koppla ett strukturelement till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Koppla ett strukturelement till innehållsströmmen BDC-operatorn. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Koppla ett strukturelement till innehållsströmmen XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Koppla ett strukturelement till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* class [WarichuChildElement](../warichuchildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


