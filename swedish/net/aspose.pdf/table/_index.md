---
title: Table
second_title: Aspose.PDF för .NET API Referens
description: Representerar en tabell som kan läggas till på sidan.
type: docs
weight: 6500
url: /sv/net/aspose.pdf/table/
---
## Table class

Representerar en tabell som kan läggas till på sidan.

```csharp
public sealed class Table : BaseParagraph
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Table](table)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Hämtar eller ställer in tabelljusteringen. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Hämtar eller ställer in tabellbakgrundsfärg |
| [Border](../../aspose.pdf/table/border) { get; set; } | Hämtar eller ställer in gränsen. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | Hämtar eller ställer in bryttext för table |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Får eller ställer tabellen vertikalt bruten; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Hämtar eller ställer in justering av tabellkolumnen. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Hämtar tabellens kolumnbredder. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Hämtar eller ställer in stilar för kanthörnen |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Får standardcellkant; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Hämtar eller ställer in standardcellsfyllningen. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Hämtar eller ställer in standardcelltexttillståndet. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Får standardcellkant; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Hämtar eller ställer in en horisontell justering av stycket |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Hämtar eller ställer in ram som ingår i kolumnbredder. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Hämtar eller sätter tabellen är trasig - kommer att trunkeras för nästa sida. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Hämtar eller sätter tabellens vänstra koordinat. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | Hämtar eller ställer in det maximala kolumnantal för table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Får antalet första rader att upprepas för flera sidor |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Hämtar stilen för repeterande rader |
| [Rows](../../aspose.pdf/table/rows) { get; } | Hämtar raderna i tabellen. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Hämtar eller ställer in koordinaten för bordsskivan. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Klona tabellen. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Få höjd. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Få bredd. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Importerar endimensionell datamatris till tabellen. Importen går en cell per varje arrays objekt och börjar från rad och kolumn definierade i parametrar. Under import, om det upptäcks att nödvändiga rader fortfarande är frånvarande (dvs. måltabellen är för liten för att absorbera all data), kommer nödvändiga rader att skapas |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | Importerar data från System.Data.DataTable till Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importer aDataTable objekt i tabellen. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importer aDataTable objekt, men inte som en helhet. Endast specificerade rader och kolumner importeras. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | Importer aDataView objektets data till tabellen. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Ställ in höjd. |

### Se även

* class [BaseParagraph](../baseparagraph)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
