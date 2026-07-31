---
title: "Classe WidgetAnnotation"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Annotations.WidgetAnnotation class. Classe che rappresenta l'annotazione widget"
type: docs
weight: 2820
url: /it/net/aspose.pdf.annotations/widgetannotation/
---
## WidgetAnnotation class

Classe che rappresenta l'annotazione widget.

```csharp
public class WidgetAnnotation : Annotation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WidgetAnnotation](widgetannotation/)(Document) | Crea annotazione (usato per Generator) |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Ottiene le azioni dell'annotazione. (2 proprietà) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ottiene o imposta lo stato di aspetto corrente dell'annotazione. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ottiene il dizionario di aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ottiene o imposta l'aspetto predefinito del campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ottiene o imposta il flag esportabile del campo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Modalità di evidenziazione dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. (per la generazione PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. (per la generazione PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Un'azione da eseguire quando l'annotazione viene attivata. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Ottiene l'indice della pagina che contiene l'Annotation. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ottiene il genitore dell'annotazione. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ottiene o imposta lo stato di sola lettura del campo. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Ottiene o imposta il rettangolo di Annotation. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ottiene o imposta lo stato obbligatorio del campo. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ottiene il dizionario di aspetto dell'annotazione. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accetta il visitatore. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aggiorna i parametri e l'aspetto, secondo la trasformazione della matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Esporta il campo modulo PDF specificato in formato JSON e scrive il risultato nello stream fornito. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Esporta il campo modulo PDF specificato in formato JSON e scrive il risultato nel file specificato. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Posiziona i contenuti di Annotation direttamente sulla pagina, l'oggetto Annotation verrà rimosso. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Restituisce il nome dello stato "checked" in base ai nomi degli stati esistenti. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Restituisce il Rectangle dell'annotazione tenendo conto della rotazione della pagina. |

### Vedi anche

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


