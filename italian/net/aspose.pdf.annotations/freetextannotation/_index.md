---
title: FreeTextAnnotation
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta unannotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di una normale annotazione di testo unannotazione di testo libero non ha uno stato aperto o chiuso invece di essere visualizzato in una finestra pop-up il testo è sempre visibile.
type: docs
weight: 430
url: /it/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di una normale annotazione di testo, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzato in una finestra pop-up, il testo è sempre visibile.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FreeTextAnnotation](freetextannotation#constructor)(Document, DefaultAppearance) | Costruttore da utilizzare con Generator. |
| [FreeTextAnnotation](freetextannotation#constructor_1)(Page, Rectangle, DefaultAppearance) | Crea una nuova annotazione FreeText sulla pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ottiene l'elenco delle azioni di annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione.[`Border`](../annotation/border) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout) { get; set; } | Matrice di punti che specifica la linea di richiamo. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Ottiene la data e l'ora in cui è stata creata l'annotazione. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance) { get; set; } | Ottiene o imposta la stringa di aspetto predefinita da utilizzare nella formattazione del testo. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject) { get; } | Oggetto che rappresenta l'aspetto predefinito dell'annotazione di FreeText. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle) { get; set; } | Ottiene o imposta una stringa di stile predefinita. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle) { get; set; } | Ottiene o imposta lo stile di fine riga per il punto di fine riga. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Un riferimento all'annotazione a cui questa annotazione è "in risposta". Entrambe le annotazioni devono trovarsi sulla stessa pagina del documento. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent) { get; set; } | Ottiene o imposta l'intento dell'annotazione di testo libero. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification) { get; set; } | Ottiene o imposta un codice che specifica la forma di quadding (giustificazione) da utilizzare per visualizzare il testo dell'annotazione. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Ottiene o imposta il valore di opacità costante da utilizzare per disegnare l'annotazione. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Annotazione a comparsa per inserire o modificare il testo associato a questa annotazione. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ottiene o imposta il rettangolo di annotazione. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Ottiene o imposta una stringa di testo RTF da visualizzare nella finestra a comparsa all'apertura dell'annotazione. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate) { get; set; } | Angolo di rotazione dell'annotazione. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle) { get; set; } | Ottiene o imposta lo stile di fine riga per il punto di fine riga. OQuesta proprietà è obsoleta, utilizzare EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Ottiene il testo che rappresenta la descrizione dell'oggetto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle) { get; set; } | Rettangolo che descrive le differenze numeriche tra due rettangoli: la voce Rect dell'annotazione e un rettangolo contenuto all'interno di quel rettangolo. Il rettangolo interno è il punto in cui deve essere visualizzato il testo dell'annotazione. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle) { get; set; } | Ottiene o imposta lo stile del testo in apparenza. quando lo stile del testo viene modificato, l'aspetto del testo viene aggiornato. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Ottiene o imposta un testo che deve essere visualizzato nella barra del titolo dell'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept)(AnnotationSelector) | Accetta l'oggetto visitatore per elaborare l'annotazione. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aggiorna parametri e aspetto, in base alla trasformata di matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona questa istanza. Metodo virtuale. Restituisci sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Posiziona il contenuto dell'annotazione direttamente nella pagina, l'oggetto dell'annotazione verrà rimosso. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Restituisce il rettangolo di annotazione tenendo conto della rotazione della pagina. |

### Guarda anche

* class [MarkupAnnotation](../markupannotation)
* spazio dei nomi [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
