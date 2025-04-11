---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber klass. Representerar ett absorberobjekt av tabellkomponenter. Utför sökningar och ger åtkomst till sökresultat via TableList-samlingen
type: docs
weight: 10790
url: /sv/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber klass

Representerar ett absorberobjekt av tabellkomponenter. Utför sökningar och ger åtkomst till sökresultat via [`TableList`](./tablelist/) samlingen.

```csharp
public class TableAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Initierar en ny instans av `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Initierar en ny instans av `TableAbsorber` med text sökalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Returnerar en readonly IList som innehåller tabeller som hittades |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Hämtar eller ställer in text sökalternativ. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Aktiverar en alternativ tabelligenkänningsmotor som är överlägsen i många scenarier och kan känna igen tabeller utan kanter. Stöder ännu inte redigering av tabeller och att hämta textstilar. Standardvärde är false; |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Tar bort en [`AbsorbedTable`](../absorbedtable/) från sidan. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Ersätter en [`AbsorbedTable`](../absorbedtable/) med [`Table`](../../aspose.pdf/table/) på sidan. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extraherar tabeller i det angivna dokumentet. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extraherar tabeller på den angivna sidan |

## Exempel

Exemplet visar hur man hittar en tabell på den första PDF-dokumentets sida och ersätter texten i en tabellcell.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)