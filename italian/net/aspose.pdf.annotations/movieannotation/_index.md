---
title: MovieAnnotation
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta unannotazione di film che contiene grafica e suoni animati da presentare sullo schermo del computer e tramite gli altoparlanti. Quando lannotazione è attivata il filmato viene riprodotto.
type: docs
weight: 730
url: /it/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Rappresenta un'annotazione di film che contiene grafica e suoni animati da presentare sullo schermo del computer e tramite gli altoparlanti. Quando l'annotazione è attivata, il filmato viene riprodotto.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MovieAnnotation](movieannotation#constructor)(Document, string) | Costruttore per l'utilizzo con Generator. |
| [MovieAnnotation](movieannotation#constructor_1)(Page, Rectangle, string) | Crea una nuova annotazione Sound nella pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ottiene l'elenco delle azioni di annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect) { get; set; } | Ottiene o imposta la larghezza e l'altezza del riquadro di delimitazione del filmato, in pixel. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [File](../../aspose.pdf.annotations/movieannotation/file) { get; set; } | Ottiene o imposta una specifica di file che identifica un file filmato autodescrittivo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster) { get; set; } | Ottiene o imposta un flag o un flusso che specifica se e come deve essere visualizzata un'immagine poster che rappresenta il film. Se vero, l'immagine del poster verrà recuperata dal file del filmato; se è falso, nessun poster deve essere visualizzato. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ottiene o imposta il rettangolo di annotazione. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate) { get; set; } | Ottiene o imposta il numero di gradi di cui il filmato deve essere ruotato in senso orario rispetto alla pagina. Il valore deve essere un multiplo di 90. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [Title](../../aspose.pdf.annotations/movieannotation/title) { get; set; } | Ottiene o imposta il titolo dell'annotazione del filmato. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept)(AnnotationSelector) | Accetta l'oggetto visitatore per elaborare l'annotazione. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aggiorna parametri e aspetto, in base alla trasformata di matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona questa istanza. Metodo virtuale. Restituisci sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Posiziona il contenuto dell'annotazione direttamente nella pagina, l'oggetto dell'annotazione verrà rimosso. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Restituisce il rettangolo di annotazione tenendo conto della rotazione della pagina. |

### Guarda anche

* class [Annotation](../annotation)
* spazio dei nomi [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
