---
title: "Klass TableElement"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LogicalStructure.TableElement-klass. Representerar Table-strukturelement i logisk struktur."
type: docs
weight: 6920
url: /sv/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Representerar Tabell-strukturselement i den logiska strukturen.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Hämtar eller anger den faktiska texten för strukturelementet. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Hämtar eller anger tabellens justering. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Hämtar eller anger den alternativa texten för strukturelementet. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Hämtar StructureAttributeCollection‑objektet. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Hämtar eller anger tabellens bakgrundsfärg. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Hämtar eller anger tabellens kant. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Hämtar eller anger tabellens vertikala brytning; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar samlingen av barn‑Element‑objekt. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Hämtar eller anger tabellens kolumnjustering. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Hämtar tabellens kolumnbredder. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Hämtar eller anger stilar för kantens hörn |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Hämtar AttributeOwnerStandard‑objektet. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Hämtar standardcellkant. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Hämtar eller anger standardcellutfyllnad. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Hämtar eller anger standardcellens texttillstånd. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Hämtar eller anger standardkolumnbredd. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Hämtar eller anger expansions‑texten för strukturelementet. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Hämtar ID‑t för strukturelementet. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Hämtar eller anger kant inkluderad i kolumnbredder. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Hämtar eller anger att tabellen är bruten – kommer att trunkeras för nästa sida. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Hämtar eller anger språket för strukturelementet. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Hämtar eller anger tabellens vänstra koordinat. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Hämtar sidan där vissa eller alla barn‑element kommer att renderas. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämta föräldraelementet. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Hämtar eller anger maximalt antal kolumner för tabellen. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Hämtar antalet första rader som upprepas för flera sidor. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Hämtar stil för upprepande rader. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Hämtar typen av strukturelement. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Hämtar eller anger titeln för strukturelementet. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Hämtar eller anger tabellens övre koordinat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägg till Element i samlingen av barn. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Ändra föräldraelement för aktuellt strukturelement |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensa alla barn. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Rensa ID för strukturelementet. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Skapar [`TableTHeadElement`](../tabletheadelement/) och lägger till den i aktuell tabell. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Skapar [`TableTFootElement`](../tabletfootelement/) och lägger till den i aktuell tabell. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Skapar [`TableTHeadElement`](../tabletheadelement/) och lägger till den i aktuell tabell. |
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

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


