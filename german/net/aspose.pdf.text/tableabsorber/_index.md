---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber-Klasse. Stellt ein Absorberobjekt von Tabellenelementen dar. Führt eine Suche durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TableList`](./tablelist/).
type: docs
weight: 10790
url: /de/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber-Klasse

Stellt ein Absorberobjekt von Tabellenelementen dar. Führt eine Suche durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Initialisiert eine neue Instanz des `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Initialisiert eine neue Instanz des `TableAbsorber` mit Textsuchoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Gibt eine schreibgeschützte IList zurück, die die gefundenen Tabellen enthält |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Ruft die Textsuchoptionen ab oder legt sie fest. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Aktiviert einen alternativen Tabellen-Erkennungs-Engine, die in zahlreichen Szenarien überlegen ist und in der Lage ist, Tabellen ohne Ränder zu erkennen. Unterstützt noch nicht das Bearbeiten von Tabellen und das Abrufen von Textstilen. Standardwert ist false; |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Entfernt eine [`AbsorbedTable`](../absorbedtable/) von der Seite. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Ersetzt eine [`AbsorbedTable`](../absorbedtable/) durch [`Table`](../../aspose.pdf/table/) auf der Seite. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extrahiert Tabellen im angegebenen Dokument. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extrahiert Tabellen auf der angegebenen Seite |

## Beispiele

Das Beispiel zeigt, wie man eine Tabelle auf der ersten Seite des PDF-Dokuments findet und den Text in einer Tabellenzelle ersetzt.

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

### Siehe auch

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)