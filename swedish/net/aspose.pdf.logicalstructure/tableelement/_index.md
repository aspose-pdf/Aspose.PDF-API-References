---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableElement klass. Representerar tabellstrukturselement i logisk struktur
type: docs
weight: 6780
url: /sv/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement klass

Representerar tabellstrukturselement i logisk struktur.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Hämtar eller ställer in den faktiska texten för struktur element. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Hämtar eller ställer in tabellens justering. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Hämtar eller ställer in alternativtexten för struktur element. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Hämtar StructureAttributeCollection objekt. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Hämtar eller ställer in tabellens bakgrundsfärg. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Hämtar eller ställer in tabellens kantlinje. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Hämtar eller ställer in tabellens vertikala brytning; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar barnkollektionen av Element objekt. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Hämtar eller ställer in tabellens kolumnjustering. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Hämtar kolumnbredderna för tabellen. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Hämtar eller ställer in stilarna för kantens hörn |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Hämtar AttributeOwnerStandard objekt. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Hämtar standard cellkantlinje. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Hämtar eller ställer in standard cellpadding. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Hämtar eller ställer in standard celltexttillstånd. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Hämtar eller ställer in standard kolumnbredd. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Hämtar eller ställer in expansions text för struktur element. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Hämtar ID för struktur element. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Hämtar eller ställer in kantlinje inkluderad i kolumnbredder. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Hämtar eller ställer in om tabellen är bruten - kommer att trunkeras för nästa sida. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Hämtar eller ställer in språket för struktur element. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Hämtar eller ställer in tabellens vänstra koordinat. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Hämtar sidan på vilken några eller alla barn element kommer att renderas. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämtar föräldraelementet. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Hämtar eller ställer in det maximala antalet kolumner för tabellen. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Hämtar det första antalet rader som upprepas för flera sidor. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Hämtar stilen för upprepande rader. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Hämtar typ av struktur element. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Hämtar eller ställer in titeln för struktur element. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Hämtar eller ställer in tabellens övre koordinat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägg till Element i barnkollektionen. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändra föräldraelement för nuvarande struktur element |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensa alla barn. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Rensa ID för struktur element. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Skapar [`TableTHeadElement`](../tabletheadelement/) och lägger till det i nuvarande tabell. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Skapar [`TableTFootElement`](../tabletfootelement/) och lägger till det i nuvarande tabell. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Skapar [`TableTHeadElement`](../tabletheadelement/) och lägger till det i nuvarande tabell. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hitta element av en given typ |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Generera ID för struktur element. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infoga Element i barnkollektionen vid angiven index. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, det motsvarande objektet från dokumentet. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, och det motsvarande objektet från dokumentet. Infogar barnobjekten av det borttagna objektet i dess tidigare förälders barnkollektion som börjar vid indexet för det borttagna objektet. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Ta bort barn vid. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Ställer in ID för struktur element. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Ställer in anpassad tagg för struktur element. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Binder ett struktur element till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Binder ett struktur element till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Binder ett struktur element till innehållsström BDC-operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Binder ett struktur element till innehållsström XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Binder ett struktur element till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se Även

* klass [BLSElement](../blselement/)
* gränssnitt [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namnrymd [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)