---
title: "Classe FreeTextAnnotation"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Annotations.FreeTextAnnotation class. Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzata in una finestra popup, il testo è sempre visibile."
type: docs
weight: 1900
url: /it/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

Rappresenta un'annotazione di testo libero che visualizza il testo direttamente sulla pagina. A differenza di un'annotazione di testo ordinaria, un'annotazione di testo libero non ha uno stato aperto o chiuso; invece di essere visualizzata in una finestra pop-up, il testo è sempre visibile.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Costruttore da usare con Generator. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Crea una nuova annotazione FreeText nella pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Ottiene l'elenco delle azioni di Annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ottiene o imposta lo stato di aspetto corrente dell'annotazione. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ottiene il dizionario di aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Array di punti che specificano la linea di richiamo. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Restituisce data e ora di creazione dell'annotazione. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Ottiene o imposta la stringa di aspetto predefinito da utilizzare nella formattazione del testo. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Oggetto che rappresenta l'aspetto predefinito dell'annotazione FreeText. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Ottiene o imposta una stringa di stile predefinito. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Ottiene o imposta lo stile di terminazione della linea per il punto finale della linea. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Un riferimento all'annotazione a cui questa annotazione è "in risposta a". Entrambe le annotazioni devono trovarsi nella stessa pagina del documento. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Ottiene o imposta l'intento dell'annotazione di testo libero. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Ottiene o imposta un codice che specifica la forma di allineamento (giustificazione) da utilizzare nella visualizzazione del testo dell'annotazione. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Ottiene o imposta il valore costante di opacità da utilizzare nella visualizzazione dell'annotazione. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Ottiene l'indice della pagina che contiene l'Annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotazione pop-up per inserire o modificare il testo associato a questa annotazione. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Ottiene o imposta il rettangolo di Annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Ottiene o imposta una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Angolo di rotazione dell'annotazione. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Ottiene o imposta lo stile di fine linea per il punto finale della linea. Questa proprietà è obsoleta, si prega di utilizzare EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ottiene il dizionario di aspetto dell'annotazione. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Restituisce il testo che rappresenta la descrizione dell'oggetto. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Rettangolo che descrive le differenze numeriche tra due rettangoli: l'elemento Rect dell'annotazione e un rettangolo contenuto all'interno di quel rettangolo. Il rettangolo interno è dove dovrebbe essere visualizzato il testo dell'annotazione. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Ottiene o imposta lo stile del testo nell'aspetto. Quando lo stile del testo viene modificato, l'aspetto del testo viene aggiornato. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Ottiene o imposta un'etichetta di testo che deve essere visualizzata nella barra del titolo della finestra pop-up dell'annotazione quando è aperta e attiva. Questa voce deve identificare l'utente che ha aggiunto l'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Accetta un oggetto visitor per elaborare l'annotazione. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aggiorna i parametri e l'aspetto, secondo la trasformazione della matrice. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Cancella lo stato e il modello di stato per l'annotazione. Ad esempio, cancella lo stato di revisione per un'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Posiziona i contenuti di Annotation direttamente sulla pagina, l'oggetto Annotation verrà rimosso. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Restituisce il Rectangle dell'annotazione tenendo conto della rotazione della pagina. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Ottiene lo stato dell'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Ottiene il modello di stato dell'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Imposta lo stato Marked e Unmarked per l'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Imposta lo stato di revisione per un'annotazione. Gli stati Marked e Unmarked sono ignorati poiché non appartengono al Review StateModel. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Imposta lo stato di revisione per un'annotazione. Gli stati Marked e Unmarked sono ignorati poiché non appartengono al Review StateModel. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle_1)(int, int, RichTextFontStyles) | Imposta la formattazione determinata dal parametro textStyle per un frammento di testo dall'indice fromInd all'indice toInd. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle)(RichTextFontStyles, string, double, Color) | Imposta la formattazione determinata dal parametro textStyle per tutto il testo dell'annotazione. |

### Vedi anche

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


