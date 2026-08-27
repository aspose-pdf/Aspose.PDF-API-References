---
title: "Classe FloatingBox"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.FloatingBox."
type: docs
weight: 4990
url: /it/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Inizializza una nuova istanza della classe `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Inizializza una nuova istanza della classe `FloatingBox` con larghezza e altezza specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Ottiene o imposta un oggetto [`Color`](../color/) che indica il colore di sfondo della floating box. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene popolata durante la lettura del documento). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Ottiene o imposta un oggetto [`BorderInfo`](../borderinfo/) che indica le informazioni del bordo della floating box. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Ottiene o imposta le informazioni di colonna |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Ottiene o imposta un valore float che indica l'altezza della floating box. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del paragrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo deve essere ripetuto nella pagina successiva. Il valore predefinito è false. L'attributo è valido solo quando sia il paragrafo stesso sia l'oggetto a cui si riferisce ReferenceParagraphID sono inclusi in RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Ottiene o imposta un oggetto [`MarginInfo`](../margininfo/) che indica il padding della floating box. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Ottiene o imposta una collezione [`Paragraphs`](./paragraphs/) che indica tutti i paragrafi nella cella. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Specifica la variante per determinare la posizione della FloatingBox sulla pagina. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Ottiene o imposta la coordinata superiore della tabella. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Ottiene o imposta un valore float che indica la larghezza della floating box. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Clona un nuovo oggetto `FloatingBox`. I paragrafi nella floating box non vengono clonati. |

### Vedi anche

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


