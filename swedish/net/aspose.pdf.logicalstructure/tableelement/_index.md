---
title: TableElement
second_title: Aspose.PDF för .NET API Referens
description: Representerar tabellstrukturelement i logisk struktur.
type: docs
weight: 4610
url: /sv/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Representerar tabellstrukturelement i logisk struktur.

```csharp
public sealed class TableElement : BLSElement
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Hämtar eller ställer in den faktiska texten för strukturelement. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Hämtar eller ställer in tabelljusteringen. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Hämtar eller ställer in den alternativa texten för strukturelement. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | BlirStructureAttributeCollection objekt. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Hämtar eller ställer in tabellens bakgrundsfärg. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Hämtar eller ställer in tabellkanten. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Får eller ställer tabellen vertikalt bruten; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Får barnsamling avElement objekt. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Hämtar eller ställer in justering av tabellkolumnen. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Hämtar tabellens kolumnbredder. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Hämtar eller ställer in stilar för kanthörnen |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | BlirAttributeOwnerStandard objekt. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Får standardcellkant. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Hämtar eller ställer in standardcellsfyllningen. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Hämtar eller ställer in standardcelltexttillståndet. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Hämtar eller ställer in standard kolumnbredd. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Hämtar eller ställer in expansionstexten för strukturelement. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Hämtar ID för strukturelement. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Hämtar eller ställer in ram som ingår i kolumnbredder. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Hämtar eller sätter tabellen är trasig - kommer att trunkeras för nästa sida. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Hämtar eller ställer in språket för strukturelement. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Hämtar eller sätter tabellens vänstra koordinat. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Hämta överordnat element. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Hämtar eller ställer in det maximala kolumnantal för tabell. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Får antalet första rader att upprepas på flera sidor. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Hämtar stilen för upprepade rader. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Hämtar typ av strukturelement. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Hämtar eller ställer in titeln för strukturelement. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Hämtar eller ställer in koordinaten för bordsskivan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | Lägg tillElement till samling av barn. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Ändra överordnat element för nuvarande strukturelement |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Rensa ID för strukturelement. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | Skapar[`TableTHeadElement`](../tabletheadelement) och lade till den i nuvarande tabell. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | Skapar[`TableTFootElement`](../tabletfootelement) och lade till den i nuvarande tabell. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | Skapar[`TableTHeadElement`](../tabletheadelement) och lade till den i nuvarande tabell. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Hitta element av en given typ |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Generera ID för strukturelement. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Anger ID för strukturelement. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Ställer in anpassad tagg för strukturelement. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* class [BLSElement](../blselement)
* namnutrymme [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
