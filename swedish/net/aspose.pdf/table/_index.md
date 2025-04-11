---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Table klass. Representerar en tabell som kan läggas till på sidan
type: docs
weight: 10280
url: /sv/net/aspose.pdf/table/
---
## Tabell klass

Representerar en tabell som kan läggas till på sidan.

```csharp
public sealed class Table : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Table](table/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Hämtar eller ställer in tabellens justering. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Hämtar eller ställer in tabellens bakgrundsfärg |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Hämtar eller ställer in gränsen. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Hämtar eller ställer in bryttext för tabellen |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Hämtar eller ställer in tabellens vertikala brott; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Hämtar eller ställer in tabellens kolumnjustering. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Hämtar kolumnbredderna för tabellen. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Hämtar eller ställer in stilarna för gränshörnen |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Hämtar standard cellgräns; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Hämtar eller ställer in standard cellpadding. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Hämtar eller ställer in standard celltexttillstånd. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Hämtar standard cellgräns; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av stycket |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Hämtar eller ställer in gränser som ingår i kolumnbredder. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Hämtar eller ställer in om tabellen är bruten - kommer att trunkeras för nästa sida. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Hämtar eller ställer in tabellens vänstra koordinat. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Hämtar eller ställer in det maximala antalet kolumner för tabellen |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Hämtar antalet första rader som upprepas för flera sidor |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Hämtar stilen för upprepande rader |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Hämtar raderna i tabellen. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Hämtar eller ställer in tabellens övre koordinat. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Klona tabellen. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Hämta höjd. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Hämta bredd. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importerar en-dimensionell array av data till tabellen. Importen går en cell per varje elements i arrayen och börjar från raden och kolumnen som definieras i parametrarna. Under importen, om det upptäckts att nödvändiga rader fortfarande saknas (dvs. måltabellen är för liten för att absorbera all data), kommer nödvändiga rader att skapas |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importerar data från System.Data.DataTable till Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importerar ett DataTable-objekt till tabellen. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importerar ett DataTable-objekt, men inte som en helhet. Endast angivna rader och kolumner importeras. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importerar data från ett DataView-objekt till tabellen. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Ställ in höjd. |

### Se Även

* klass [BaseParagraph](../baseparagraph/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)