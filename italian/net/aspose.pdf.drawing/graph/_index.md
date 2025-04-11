---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph class. Represents graph  graphics generator paragraph
type: docs
weight: 3940
url: /it/net/aspose.pdf.drawing/graph/
---
## Classe Graph

Rappresenta un paragrafo generatore di grafica grafica.

```csharp
public sealed class Graph : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Inizializza una nuova istanza della classe `Graph`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Ottiene o imposta il bordo. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Ottiene o imposta un oggetto [`GraphInfo`](./graphinfo/) che indica le informazioni sul grafico, come colore, larghezza della linea, ecc. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Ottiene o imposta un valore float che indica l'altezza del grafico. L'unità è il punto. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Ottiene o imposta il cambiamento della posizione corrente dopo l'elaborazione del paragrafo. (predefinito vero) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il predefinito è falso. (per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il predefinito è falso. (per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il predefinito è falso. (per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il predefinito è falso. (per la generazione di pdf) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Ottiene o imposta una collezione [`Shapes`](./shapes/) che indica tutte le forme nel grafico. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Ottiene o imposta un valore stringa che indica il titolo del grafico. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Ottiene o imposta la coordinata superiore della tabella. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Ottiene o imposta un valore float che indica la larghezza del grafico. L'unità è il punto. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Clona il grafico. |

### Vedi Anche

* classe [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)