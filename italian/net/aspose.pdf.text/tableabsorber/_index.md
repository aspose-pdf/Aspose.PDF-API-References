---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TableAbsorber. Rappresenta un oggetto assorbitore di elementi di tabella. Esegue la ricerca e fornisce accesso ai risultati della ricerca tramite la collezione TableList
type: docs
weight: 10790
url: /it/net/aspose.pdf.text/tableabsorber/
---
## Classe TableAbsorber

Rappresenta un oggetto assorbitore di elementi di tabella. Esegue la ricerca e fornisce accesso ai risultati della ricerca tramite la collezione [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Inizializza una nuova istanza di `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Inizializza una nuova istanza di `TableAbsorber` con opzioni di ricerca del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Restituisce un IList di sola lettura contenente le tabelle trovate |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Abilita un motore di riconoscimento delle tabelle alternativo che è superiore in numerosi scenari e in grado di riconoscere tabelle senza bordi. Non supporta ancora la modifica delle tabelle e l'ottenimento degli stili di testo. Il valore predefinito è false; |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Rimuove un [`AbsorbedTable`](../absorbedtable/) dalla pagina. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Sostituisce un [`AbsorbedTable`](../absorbedtable/) con [`Table`](../../aspose.pdf/table/) sulla pagina. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Estrae tabelle nel documento specificato. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Estrae tabelle sulla pagina specificata |

## Esempi

L'esempio dimostra come trovare una tabella nella prima pagina del documento PDF e sostituire il testo in una cella della tabella.

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

### Vedi Anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)