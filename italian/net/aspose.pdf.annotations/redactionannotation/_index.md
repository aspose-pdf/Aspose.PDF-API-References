---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.RedactionAnnotation. Rappresenta l'annotazione di redazione
type: docs
weight: 2400
url: /it/net/aspose.pdf.annotations/redactionannotation/
---
## Classe RedactionAnnotation

Rappresenta l'annotazione di redazione.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | Costruttore per RedactionAnnotation. Per l'uso in Generator. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | Costruttore per RedactAnnotation. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Ottiene l'elenco delle azioni dell'annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ottiene o imposta lo stato di apparizione corrente dell'annotazione. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Ottiene o imposta il colore del bordo che viene disegnato quando la redazione non è attiva. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Ottiene la data e l'ora in cui è stata creata l'annotazione. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Ottiene o imposta la stringa di apparizione predefinita da utilizzare per formattare il testo. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Ottiene o imposta il colore per riempire l'annotazione. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dell'annotazione. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Ottiene o imposta la dimensione del carattere per OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ottiene il nome completamente qualificato dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Un riferimento all'annotazione a cui questa annotazione è "in risposta". Entrambe le annotazioni devono trovarsi sulla stessa pagina del documento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata recentemente modificata. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ottiene o imposta il nome dell'annotazione sulla pagina. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Ottiene o imposta il valore di opacità costante da utilizzare per dipingere l'annotazione. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Ottiene o imposta il testo da stampare sull'annotazione di redazione. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotazione pop-up per inserire o modificare il testo associato a questa annotazione. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Un array di numeri 8xN che specificano le coordinate della regione di contenuto che si intende rimuovere. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Ottiene o imposta il rettangolo dell'annotazione. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Se vero, il testo sovrapposto verrà ripetuto sull'annotazione. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e una specificata da InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Ottiene o imposta una stringa di testo ricco da visualizzare nella finestra pop-up quando l'annotazione è aperta. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Ottiene il testo che rappresenta la descrizione dell'oggetto. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Ottiene o imposta. Allineamento del testo sovrapposto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Ottiene o imposta un testo che deve essere visualizzato nella barra del titolo dell'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Accetta un oggetto visitatore per elaborare l'annotazione. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aggiorna i parametri e l'apparenza, secondo la trasformazione della matrice. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Pulisce lo stato e il modello di stato per l'annotazione. Ad esempio, pulisce lo stato di revisione per un'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Appiattisce l'annotazione, cioè rimuove l'annotazione e aggiunge il suo |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Ottiene lo stato dell'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Ottiene il modello di stato dell'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Appiattisce l'annotazione e redige i contenuti della pagina (cioè rimuove testo e immagini sotto l'annotazione redatta) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Imposta lo stato Marcato e Non Marcato per l'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Imposta lo stato di revisione per un'annotazione. Gli stati Marcato e Non Marcato vengono ignorati poiché non appartengono al modello di stato di revisione. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Imposta lo stato di revisione per un'annotazione. Gli stati Marcato e Non Marcato vengono ignorati poiché non appartengono al modello di stato di revisione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |

### Vedi anche

* classe [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)