---
title: Class TextMarkupAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.TextMarkupAnnotation. Classe base astratta per annotazioni di markup del testo
type: docs
weight: 2670
url: /it/net/aspose.pdf.annotations/textmarkupannotation/
---
## Classe TextMarkupAnnotation

Classe base astratta per annotazioni di markup del testo.

```csharp
public abstract class TextMarkupAnnotation : MarkupAnnotation
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Ottiene l'elenco delle azioni di annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ottiene o imposta lo stato di apparizione corrente dell'annotazione. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Ottiene la data e l'ora in cui è stata creata l'annotazione. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ottiene il nome completamente qualificato dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Un riferimento all'annotazione a cui questa annotazione è "in risposta". Entrambe le annotazioni devono trovarsi sulla stessa pagina del documento. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione di pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata recentemente modificata. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ottiene o imposta il nome dell'annotazione sulla pagina. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Ottiene o imposta il valore di opacità costante da utilizzare per dipingere l'annotazione. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotazione pop-up per inserire o modificare il testo associato a questa annotazione. |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints/) { get; set; } | Ottiene o imposta un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero racchiude una parola o un gruppo di parole contigue nel testo sottostante all'annotazione. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Ottiene o imposta il rettangolo dell'annotazione. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e una specificata da InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Ottiene o imposta una stringa di testo ricco da visualizzare nella finestra pop-up quando l'annotazione è aperta. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Ottiene il testo che rappresenta la descrizione dell'oggetto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Ottiene o imposta un testo che deve essere visualizzato nella barra del titolo dell'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | Accetta il visitatore per l'elaborazione dell'annotazione. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize/)(Matrix) | Aggiorna i QuadPoints, secondo la trasformazione della matrice. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Pulisce lo stato e il modello di stato per l'annotazione. Ad esempio, pulisce lo stato di revisione per un'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Posiziona il contenuto dell'annotazione direttamente sulla pagina, l'oggetto annotazione sarà rimosso. |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext/)() | Ottiene il testo sotto l'annotazione di markup come stringa. |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments/)() | Ottiene il testo sotto l'annotazione di markup come [`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection/). |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Ottiene lo stato dell'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Ottiene il modello di stato dell'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Imposta lo stato Marcato e Non Marcato per l'annotazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Imposta lo stato di revisione per un'annotazione. Gli stati Marcato e Non Marcato vengono ignorati poiché non appartengono al Modello di Stato di Revisione. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Imposta lo stato di revisione per un'annotazione. Gli stati Marcato e Non Marcato vengono ignorati poiché non appartengono al Modello di Stato di Revisione. Nota, lo stato è memorizzato in un'altra annotazione di testo che ha chiavi di stato e modello di stato. |

### Vedi anche

* classe [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)