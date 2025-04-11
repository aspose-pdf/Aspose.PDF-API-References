---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.FloatingBox.
type: docs
weight: 4870
url: /it/net/aspose.pdf/floatingbox/
---
## Classe FloatingBox

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
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Ottiene o imposta un oggetto [`Color`](../color/) che indica il colore di sfondo della casella flottante. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non compilata durante la lettura del documento). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Ottiene o imposta un oggetto [`BorderInfo`](../borderinfo/) che indica le informazioni sul bordo della casella flottante. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Ottiene o imposta le informazioni sulla colonna |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Ottiene o imposta un valore float che indica l'altezza della casella flottante. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ottiene o imposta un allineamento orizzontale del paragrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione pdf) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo deve essere ripetuto nella pagina successiva. Il valore predefinito è falso. L'attributo è valido solo quando il paragrafo stesso e l'oggetto a cui si riferisce il suo ReferenceParagraphID sono entrambi inclusi in RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Ottiene o imposta la coordinata sinistra della tabella. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione pdf) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Ottiene o imposta un oggetto [`MarginInfo`](../margininfo/) che indica il padding della casella flottante. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Ottiene o imposta una collezione di [`Paragraphs`](./paragraphs/) che indica tutti i paragrafi nella cella. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Specifica la variante per determinare la posizione della FloatingBox sulla pagina. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Ottiene o imposta la coordinata superiore della tabella. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Ottiene o imposta un valore float che indica la larghezza della casella flottante. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Clona un nuovo oggetto `FloatingBox`. I paragrafi nella casella flottante non vengono clonati. |

### Vedi Anche

* classe [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)