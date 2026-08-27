---
title: "Classe TextState"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextState. Rappresenta lo stato di un testo"
type: docs
weight: 11260
url: /it/net/aspose.pdf.text/textstate/
---
## TextState class

Rappresenta lo stato di un testo

```csharp
public class TextState
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextState](textstate/#constructor)() | Crea un oggetto di stato del testo. |
| [TextState](textstate/#constructor_2)(Color) | Crea un oggetto di stato del testo con specifica del colore di primo piano. |
| [TextState](textstate/#constructor_1)(double) | Crea un oggetto di stato del testo con specifica della dimensione del carattere. |
| [TextState](textstate/#constructor_4)(string) | Crea un oggetto di stato del testo con specifica della famiglia del carattere. |
| [TextState](textstate/#constructor_3)(Color, double) | Crea un oggetto di stato del testo con specifica del colore di primo piano e della dimensione del carattere. |
| [TextState](textstate/#constructor_6)(string, double) | Crea un oggetto di stato del testo con specifica della famiglia del carattere e della dimensione del carattere. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Crea un oggetto di stato del testo con specifica della famiglia del carattere e dello stile del carattere. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Imposta il colore di sfondo del testo. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Ottiene o imposta la spaziatura dei caratteri del testo. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del carattere. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del carattere. Il valore predefinito è Descender. Se il valore Descent del carattere è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri caratteri. In questo caso, è possibile selezionare CoordinateOrigin BaseLine per una migliore resa del testo. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Ottiene o imposta il carattere del testo. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Ottiene o imposta la dimensione del carattere del testo. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Imposta lo stile del carattere del testo. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Ottiene o imposta il colore di primo piano del testo. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del testo. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Ottiene o imposta la scala orizzontale del testo. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Ottiene o imposta l'invisibilità del testo. Questo riflette fondamentalmente lo stato di [`RenderingMode`](./renderingmode/), eccetto alcuni casi speciali (come il ritaglio). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Ottiene o imposta l'interlinea del testo. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Ottiene o imposta la modalità di rendering del testo. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Ottiene o imposta il barrato per il testo, rappresentato dall'oggetto [`TextSegment`](../textsegment/) |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Ottiene o imposta il colore di primo piano del testo. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Ottiene o imposta il pedice del testo. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Ottiene o imposta il apice del testo. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | È possibile inserire questo tag nel testo per dichiarare la tabulazione. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Ottiene o imposta la sottolineatura per il testo, rappresentata dall'oggetto [`TextFragment`](../textfragment/) |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Ottiene o imposta la spaziatura delle parole del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Applica le impostazioni da un altro textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Misura l'altezza del carattere. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Misura la stringa. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valore predefinito della tabulazione nelle larghezze del carattere spazio del font predefinito. |

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


