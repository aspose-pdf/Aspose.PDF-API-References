---
title: PopupAnnotation
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta lannotazione a comparsa che visualizza il testo in una finestra a comparsa per limmissione e la modifica.
type: docs
weight: 940
url: /it/net/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class

Rappresenta l'annotazione a comparsa che visualizza il testo in una finestra a comparsa per l'immissione e la modifica.

```csharp
public sealed class PopupAnnotation : Annotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PopupAnnotation](popupannotation#constructor)(Document) | Costruttore. per l'utilizzo in Generator. |
| [PopupAnnotation](popupannotation#constructor_1)(Page, Rectangle) | Crea una nuova annotazione Popup nella pagina specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ottiene l'elenco delle azioni di annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| override [AnnotationType](../../aspose.pdf.annotations/popupannotation/annotationtype) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
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
| [Open](../../aspose.pdf.annotations/popupannotation/open) { get; set; } | Ottiene o imposta un flag che specifica se l'annotazione a comparsa deve essere inizialmente visualizzata aperta. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Parent](../../aspose.pdf.annotations/popupannotation/parent) { get; set; } | Ottiene o imposta l'annotazione principale a cui deve essere associata questa annotazione a comparsa. Se questa voce è presente, le voci Contenuto, M, C e T dell'annotazione principale sovrascriveranno quelle dell'annotazione a comparsa stessa. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ottiene o imposta il rettangolo di annotazione. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/popupannotation/accept)(AnnotationSelector) | Accetta l'oggetto visitatore per elaborare l'annotazione. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aggiorna parametri e aspetto, in base alla trasformata di matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona questa istanza. Metodo virtuale. Restituisci sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Posiziona il contenuto dell'annotazione direttamente nella pagina, l'oggetto dell'annotazione verrà rimosso. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Restituisce il rettangolo di annotazione tenendo conto della rotazione della pagina. |

### Guarda anche

* class [Annotation](../annotation)
* spazio dei nomi [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
