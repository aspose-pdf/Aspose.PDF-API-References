---
title: "Klass TableAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TableAbsorber class. Representerar ett absorberande objekt för tabell‑element. Utför sökning och ger åtkomst till sökresultat via TableList‑samling"
type: docs
weight: 10970
url: /sv/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

Representerar ett absorberande objekt för tabell‑element. Utför sökning och ger åtkomst till sökresultat via [`TableList`](./tablelist/)‑samling.

```csharp
public class TableAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Initierar en ny instans av `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Initierar en ny instans av `TableAbsorber` med alternativ för textsökning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Returnerar en readonly IList som innehåller tabeller som hittades |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Hämtar eller anger alternativ för textsökning. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Aktivera en alternativ tabelligenkänningsmotor som är överlägsen i många scenarier och kan känna igen tabeller utan kanter. Stöder ännu inte redigering av tabeller och hämtning av textstilar. Standardvärdet är false; |

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
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TableAbsorber‑objekt för att hitta tabeller
TableAbsorber absorber = new TableAbsorber();

// Besök första sidan med absorberaren
absorber.Visit(pdfDocument.Pages[1]);

// Få åtkomst till den första tabellen på sidan, dess första cell och textfragmenten i den
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Ändra texten i det första textfragmentet i cellen
fragment.Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


