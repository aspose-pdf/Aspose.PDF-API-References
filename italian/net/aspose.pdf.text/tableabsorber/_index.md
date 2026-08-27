---
title: "Classe TableAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TableAbsorber. Rappresenta un oggetto assorbitore di elementi tabella. Esegue la ricerca e fornisce l'accesso ai risultati della ricerca tramite la collezione TableList"
type: docs
weight: 10970
url: /it/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

Rappresenta un oggetto assorbitore di elementi tabella. Esegue la ricerca e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TableList`](./tablelist/).

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
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Abilita un motore alternativo di riconoscimento delle tabelle, superiore in numerosi scenari e capace di riconoscere tabelle senza bordi. Non supporta ancora la modifica delle tabelle e l'ottenimento degli stili del testo. Il valore predefinito è false; |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Rimuove un [`AbsorbedTable`](../absorbedtable/) dalla pagina. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Sostituisce un [`AbsorbedTable`](../absorbedtable/) con [`Table`](../../aspose.pdf/table/) nella pagina. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Estrae le tabelle nel documento specificato. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Estrae le tabelle nella pagina specificata |

## Esempi

L'esempio dimostra come trovare una tabella nella prima pagina del documento PDF e sostituire il testo in una cella della tabella.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TableAbsorber per trovare le tabelle
TableAbsorber absorber = new TableAbsorber();

// Visita la prima pagina con l'assorbitore
absorber.Visit(pdfDocument.Pages[1]);

// Ottieni l'accesso alla prima tabella nella pagina, alla sua prima cella e ai frammenti di testo al suo interno
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Modifica il testo del primo frammento di testo nella cella
fragment.Text = "hi world";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


