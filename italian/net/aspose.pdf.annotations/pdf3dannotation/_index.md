---
title: PDF3DAnnotation
second_title: Aspose.PDF per .NET API Reference
description: Annotazione Classe PDF3D. Questa classe non può essere ereditata.
type: docs
weight: 770
url: /it/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation class

Annotazione Classe PDF3D. Questa classe non può essere ereditata.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation#constructor)(Page, Rectangle, PDF3DArtwork) | Inizializza una nuova istanza di[`PDF3DAnnotation`](../pdf3dannotation) classe. |
| [PDF3DAnnotation](pdf3dannotation#constructor_1)(Page, Rectangle, PDF3DArtwork, PDF3DActivation) | Inizializza una nuova istanza di[`PDF3DAnnotation`](../pdf3dannotation) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Ottiene l'elenco delle azioni di annotazione. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| override [AnnotationType](../../aspose.pdf.annotations/pdf3dannotation/annotationtype) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Content](../../aspose.pdf.annotations/pdf3dannotation/content) { get; set; } | Ottiene o imposta il contenuto. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [LightingScheme](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme) { get; } | Ottiene lo schema di illuminazione. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Ottiene l'indice della pagina che contiene l'annotazione. |
| [Pdf3DArtwork](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork) { get; } | Ottiene la grafica 3D. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Ottiene o imposta il rettangolo di annotazione. |
| [RenderMode](../../aspose.pdf.annotations/pdf3dannotation/rendermode) { get; } | Ottiene la modalità di rendering. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| [ViewArray](../../aspose.pdf.annotations/pdf3dannotation/viewarray) { get; } | Ottiene l'array di visualizzazione. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pdf3dannotation/accept)(AnnotationSelector) | Accetta il visitatore per l'elaborazione delle annotazioni. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aggiorna parametri e aspetto, in base alla trasformata di matrice. |
| [ClearImagePreview](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview)() | Cancella l'anteprima dell'immagine. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona questa istanza. Metodo virtuale. Restituisci sempre null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Posiziona il contenuto dell'annotazione direttamente nella pagina, l'oggetto dell'annotazione verrà rimosso. |
| [GetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview)() | Ottiene l'anteprima dell'immagine. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Restituisce il rettangolo di annotazione tenendo conto della rotazione della pagina. |
| [SetDefaultViewIndex](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex)(int) | Imposta l'indice della vista predefinita. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview)(Stream) | Imposta l'anteprima dell'immagine. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview_1)(string) | Imposta l'anteprima dell'immagine. |

### Guarda anche

* class [Annotation](../annotation)
* spazio dei nomi [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
