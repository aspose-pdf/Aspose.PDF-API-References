---
title: "Classe Graph"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Drawing.Graph classe. Rappresenta un grafico generatore di grafica per paragrafi"
type: docs
weight: 4060
url: /it/net/aspose.pdf.drawing/graph/
---
## Graph class

Rappresenta il grafico - paragrafo del generatore grafico.

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
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Ottiene o imposta un oggetto [`GraphInfo`](./graphinfo/) che indica le informazioni del grafico, come colore, larghezza della linea, ecc. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Ottiene o imposta un valore float che indica l'altezza del grafico. L'unità è il punto. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del paragrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Ottiene o imposta la modifica della posizione corrente dopo l'elaborazione del paragrafo. (predefinito true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Ottiene o imposta una collezione [`Shapes`](./shapes/) che indica tutte le forme nel grafico. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Ottiene o imposta un valore stringa che indica il titolo del grafico. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Ottiene o imposta la coordinata superiore della tabella. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Ottiene o imposta un valore float che indica la larghezza del grafico. L'unità è il punto. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Clona il grafico. |

### Vedi anche

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)


