---
title: Class ParagraphElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.ParagraphElement klass. Representerar paragrafstrukturens element i den logiska strukturen
type: docs
weight: 6540
url: /sv/net/aspose.pdf.logicalstructure/paragraphelement/
---
## ParagraphElement klass

Representerar paragrafstrukturens element i den logiska strukturen.

```csharp
public sealed class ParagraphElement : BLSTextElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Hämtar eller sätter den faktiska texten för strukturens element. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Hämtar eller sätter den alternativa texten för strukturens element. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Hämtar StructureAttributeCollection-objektet. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar barnkollektionen av Element-objekt. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Hämtar AttributeOwnerStandard-objektet. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Hämtar eller sätter expansions texten för strukturens element. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Hämtar ID för strukturens element. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Hämtar eller sätter språket för strukturens element. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Hämtar sidan där några eller alla barnelement kommer att renderas. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämtar föräldraelementet. |
| [StructureTextState](../../aspose.pdf.logicalstructure/blstextelement/structuretextstate/) { get; } | Hämtar StructureTextState-objektet för det aktuella elementet. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Hämtar typen av strukturens element. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Hämtar eller sätter titeln för strukturens element. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/blstextelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägger till Element i barnkollektionen. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändrar föräldraelementet för det aktuella strukturens element |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensar alla barn. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Rensar ID för strukturens element. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hittar element av en given typ |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genererar ID för strukturens element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infogar Element i barnkollektionen vid angiven index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, det motsvarande objektet från dokumentet. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, och det motsvarande objektet från dokumentet. Infogar barnobjekten från det borttagna objektet i dess tidigare förälders barnkollektion som börjar vid indexet för det borttagna objektet. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Tar bort barn vid. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Sätter ID för strukturens element. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Sätter anpassad tagg för strukturens element. |
| [SetText](../../aspose.pdf.logicalstructure/blstextelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Binder ett strukturens element till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Binder ett strukturens element till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Binder ett strukturens element till innehållsström BDC-operatorn. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Binder ett strukturens element till innehållsström XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Binder ett strukturens element till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se Även

* klass [BLSTextElement](../blstextelement/)
* namnrum [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* sammansättning [Aspose.PDF](../../)