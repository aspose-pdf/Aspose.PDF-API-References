---
title: Table
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una tabella che può essere aggiunta alla pagina.
type: docs
weight: 6500
url: /it/net/aspose.pdf/table/
---
## Table class

Rappresenta una tabella che può essere aggiunta alla pagina.

```csharp
public sealed class Table : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Table](table)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Ottiene o imposta l'allineamento della tabella. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo della tabella |
| [Border](../../aspose.pdf/table/border) { get; set; } | Ottiene o imposta il bordo. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | Ottiene o imposta il testo dell'interruzione per la tabella |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Ottiene o imposta la verticale della tabella interrotta; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Ottiene o imposta la regolazione della colonna della tabella. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Ottiene le larghezze delle colonne della tabella. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Ottiene o imposta gli stili degli angoli del bordo |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Ottiene il bordo della cella predefinito; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Ottiene o imposta il riempimento predefinito della cella. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Ottiene o imposta lo stato predefinito del testo della cella. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Ottiene il bordo della cella predefinito; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Ottiene o imposta il bordo incluso nelle larghezze di colonna. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Ottiene o imposta la tabella è interrotta - verrà troncata per la pagina successiva. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | Ottiene o imposta il numero massimo di colonne per table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Ottiene il conteggio delle prime righe ripetuto per diverse pagine |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Ottiene lo stile per la ripetizione delle righe |
| [Rows](../../aspose.pdf/table/rows) { get; } | Ottiene le righe della tabella. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Ottiene o imposta la coordinata superiore del tavolo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Clona la tabella. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Ottieni altezza. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Ottieni larghezza. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Importa una matrice unidimensionale di dati nella tabella. L'importazione passa di una cella per ogni elemento dell'array e inizia dalla riga e dalla colonna definite nei parametri. Durante l'importazione, se rilevate che le righe necessarie sono ancora assenti (ovvero la tabella di destinazione è troppo piccola per assorbire tutti i dati), verranno create le righe necessarie |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | Importa i dati da System.Data.DataTable in Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importazioni aDataTable oggetto nella tabella. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importazioni aDataTable oggetto, ma non come entità intera. Vengono importate solo righe e colonne specificate. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | Importazioni aDataView i dati dell'oggetto nella tabella. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Imposta altezza. |

### Guarda anche

* class [BaseParagraph](../baseparagraph)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
