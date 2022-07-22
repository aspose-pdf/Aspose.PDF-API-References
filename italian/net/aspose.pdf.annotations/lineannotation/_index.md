---
title: LineAnnotation
second_title: Aspose.PDF per .NET API Reference
description: Classe che rappresenta lannotazione della riga.
type: docs
weight: 600
url: /it/net/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class

Classe che rappresenta l'annotazione della riga.

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LineAnnotation](lineannotation#constructor)(Document, Point, Point) | Costruttore per l'utilizzo con Generator. |
| [LineAnnotation](lineannotation#constructor_1)(Page, Rectangle, Point, Point) | Crea una nuova annotazione di riga nella pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ottiene l'elenco delle azioni di annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione.[`Border`](../annotation/border) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset) { get; set; } | Ottiene o imposta l'offset del testo della didascalia dalla sua posizione normale. |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition) { get; set; } | Ottiene o imposta la posizione della didascalia dell'annotazione. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Ottiene la data e l'ora in cui è stata creata l'annotazione. |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending) { get; set; } | Ottiene o imposta il punto finale della riga. |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle) { get; set; } | Ottiene o imposta lo stile finale per il punto finale della linea. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Un riferimento all'annotazione a cui questa annotazione è "in risposta". Entrambe le annotazioni devono trovarsi sulla stessa pagina del documento. |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent) { get; set; } | Ottiene o imposta l'intento dell'annotazione della riga. |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor) { get; set; } | Ottiene o imposta il colore interno dell'annotazione. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline) { get; set; } | Ottiene o imposta la lunghezza della linea guida. |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension) { get; set; } | Ottiene o imposta la lunghezza dell'estensione della linea guida. |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset) { get; set; } | Ottiene o imposta l'offset della linea guida. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure) { get; set; } | Unità di misura specificate per questa annotazione. |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Ottiene o imposta il valore di opacità costante da utilizzare per disegnare l'annotazione. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Annotazione a comparsa per inserire o modificare il testo associato a questa annotazione. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ottiene o imposta il rettangolo di annotazione. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Ottiene o imposta una stringa di testo RTF da visualizzare nella finestra a comparsa all'apertura dell'annotazione. |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption) { get; set; } | Ottiene o imposta un flag booleano che determina che il contenuto deve essere mostrato come didascalia. |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting) { get; set; } | Ottiene o imposta il punto iniziale della linea. |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle) { get; set; } | Ottiene o imposta lo stile di fine riga per il punto iniziale della riga. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Ottiene il testo che rappresenta la descrizione dell'oggetto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Ottiene o imposta un testo che deve essere visualizzato nella barra del titolo dell'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept)(AnnotationSelector) | Accetta il visitatore per l'elaborazione delle annotazioni. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize)(Matrix) | Aggiorna i punti di inizio e fine, in base alla trasformazione della matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona questa istanza. Metodo virtuale. Restituisci sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Posiziona il contenuto dell'annotazione direttamente nella pagina, l'oggetto dell'annotazione verrà rimosso. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Restituisce il rettangolo di annotazione tenendo conto della rotazione della pagina. |

### Guarda anche

* class [MarkupAnnotation](../markupannotation)
* spazio dei nomi [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
