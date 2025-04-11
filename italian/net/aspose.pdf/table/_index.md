---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Table. Rappresenta una tabella che può essere aggiunta alla pagina
type: docs
weight: 10280
url: /it/net/aspose.pdf/table/
---
## Classe Tabella

Rappresenta una tabella che può essere aggiunta alla pagina.

```csharp
public sealed class Table : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Table](table/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Ottiene o imposta l'allineamento della tabella. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Ottiene o imposta il colore di sfondo della tabella |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Ottiene o imposta il bordo. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Ottiene o imposta il testo di interruzione per la tabella |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Ottiene o imposta la tabella verticale rotta; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Ottiene o imposta l'aggiustamento delle colonne della tabella. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Ottiene le larghezze delle colonne della tabella. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Ottiene o imposta gli stili degli angoli del bordo |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Ottiene il bordo predefinito della cella; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Ottiene o imposta il padding predefinito della cella. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Ottiene o imposta lo stato del testo predefinito della cella. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Ottiene il bordo predefinito della cella; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Ottiene o imposta il bordo incluso nelle larghezze delle colonne. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Ottiene o imposta se la tabella è rotta - sarà troncata per la pagina successiva. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione pdf) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Ottiene o imposta il numero massimo di colonne per la tabella |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Ottiene il numero di righe ripetute per diverse pagine |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Ottiene lo stile per le righe ripetute |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Ottiene le righe della tabella. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Ottiene o imposta la coordinata superiore della tabella. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Clona la tabella. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Ottiene l'altezza. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Ottiene la larghezza. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importa un array unidimensionale di dati nella tabella. L'importazione avviene una cella per ogni elemento dell'array e inizia dalla riga e colonna definite nei parametri. Durante l'importazione, se si rileva che le righe necessarie sono ancora assenti (cioè la tabella di destinazione è troppo piccola per assorbire tutti i dati), verranno create le righe necessarie |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importa dati da System.Data.DataTable in Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importa un oggetto DataTable nella tabella. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importa un oggetto DataTable, ma non come entità intera. Solo le righe e colonne specificate vengono importate. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importa i dati di un oggetto DataView nella tabella. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Imposta l'altezza. |

### Vedi Anche

* classe [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)