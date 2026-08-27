---
title: "Klass Table"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Table-klass. Representerar en tabell som kan läggas till på sidan"
type: docs
weight: 10460
url: /sv/net/aspose.pdf/table/
---
## Table class

Representerar en tabell som kan läggas till på sidan.

```csharp
public sealed class Table : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Table](table/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Hämtar eller anger tabellens justering. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Hämtar eller anger tabellens bakgrundsfärg |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Hämtar eller anger kanten. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Hämtar eller anger radbrytningstext för tabell |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Hämtar eller anger tabellens vertikala brytning; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Hämtar eller anger tabellens kolumnjustering. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Hämtar tabellens kolumnbredder. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Hämtar eller anger stilar för kantens hörn |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Hämtar standardcellram; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Hämtar eller anger standardcellutfyllnad. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Hämtar eller anger standardcellens texttillstånd. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Hämtar standardcellram; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av stycket. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Hämtar eller anger kant inkluderad i kolumnbredder. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Hämtar eller anger att tabellen är bruten – kommer att trunkeras för nästa sida. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Hämtar eller anger tabellens vänstra koordinat. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Hämtar eller anger det maximala antalet kolumner för tabellen |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Hämtar antalet första rader som upprepas för flera sidor |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Hämtar stilen för upprepande rader |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Hämtar raderna i tabellen. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Hämtar eller anger tabellens övre koordinat. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Klona tabellen. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Hämta höjd. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Hämta bredd. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importerar endimensionell array av data till tabellen. Importen går en cell per varje array‑element och startar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäcks att nödvändiga rader fortfarande saknas (dvs. mål‑tabellen är för liten för att rymma all data), kommer nödvändiga rader att skapas |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importerar data från System.Data.DataTable till Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importerar ett DataTable‑objekt till tabellen. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importerar ett DataTable‑objekt, men inte som en hel enhet. Endast angivna rader och kolumner importeras. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importerar data från ett DataView‑objekt till tabellen. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Ange höjd. |

### Se även

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


