---
title: ChoiceField
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta la classe base per i campi di scelta.
type: docs
weight: 2940
url: /it/net/aspose.pdf.forms/choicefield/
---
## ChoiceField class

Rappresenta la classe base per i campi di scelta.

```csharp
public abstract class ChoiceField : Field
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ChoiceField](choicefield#constructor)(Document) | Crea campo di scelta (per Generator) |
| [ChoiceField](choicefield#constructor_1)(Document, Rectangle) | Costruttore per ChoiceField. |
| [ChoiceField](choicefield#constructor_2)(Page, Rectangle) | Costruttore per ChoiceField. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Ottiene le azioni di annotazione. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Ottiene o imposta il nome alternativo del campo (un campo alternativo nome che deve essere utilizzato al posto del nome del campo effettivo ogni volta che il campo deve essere identificato nell'interfaccia utente). Il nome alternativo viene utilizzato come descrizione comando del campo in Adobe Acrobat . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Ottiene o imposta l'indice di questa annotazione nella pagina. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } | Ottiene o imposta il commit al flag di modifica della selezione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Ottiene o imposta il numero di sottocampi in questo campo. (Ad esempio il numero di elementi nel campo del pulsante di opzione). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Ottiene o imposta l'aspetto predefinito del campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Ottiene o imposta il flag esportabile del campo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Ottiene il nome completo dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Modalità di evidenziazione delle annotazioni. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Ottiene o imposta un valore booleano che indica che questo campo è un campo non terminale, ad esempio un gruppo di campi. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Ottiene o imposta un paragrafo in linea. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. L'impostazione predefinita è false.(per la generazione di pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Proprietà per il supporto del generatore. Utilizzato quando il campo viene aggiunto all'intestazione o al piè di pagina. Se true, questo campo verrà creato una volta e il suo aspetto sarà visibile su tutte le pagine del documento. Se false, verrà creato un campo separato per ogni pagina del documento. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Restituisce vero se il dizionario è sincronizzato. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Ottiene il sottocampo contenuto in questo campo in base al nome del sottocampo. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Ottiene o imposta il nome di mappatura del campo che deve essere utilizzato durante l'esportazione dei dati del campo modulo interattivo dal documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } | Ottiene o imposta il flag di selezione multipla. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Ottiene o imposta il nome dell'annotazione nella pagina. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Un'azione che deve essere eseguita quando l'annotazione è attivata. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options) { get; } | Ottiene la raccolta di opzioni di scelta. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Ottiene l'indice della pagina che contiene questo campo. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Ottiene l'annotazione padre. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Ottiene o imposta il nome parziale del campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Ottiene o imposta lo stato di sola lettura del campo. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Ottiene o imposta il rettangolo del campo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Ottiene o imposta lo stato richiesto del campo. |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected) { get; set; } | Ottiene o imposta l'indice dell'opzione selezionata. Questa proprietà consente di modificare la selezione. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems) { get; set; } | Ottiene o imposta una matrice di elementi selezionati. Per l'elenco a selezione multipla, l'array contiene più di un elemento. Per l'elenco a selezione singola contiene un singolo elemento. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Ottiene il dizionario dell'aspetto dell'annotazione. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Oggetto di sincronizzazione. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Ottiene o imposta l'ordine di tabulazione del campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| override [Value](../../aspose.pdf.forms/choicefield/value) { get; set; } | Ottiene o imposta il valore del campo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Il grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Accetta visitatore. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption#addoption)(string) | Aggiunge una nuova opzione con il nome specificato. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption#addoption_1)(string, string) | Aggiunge una nuova opzione con il valore di esportazione e il nome specificati. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Aggiorna parametri e aspetto, in base alla trasformata di matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona questa istanza. Metodo virtuale. Restituisci sempre null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Copia i sottocampi di questo campo nell'array a partire dall'indice specificato. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) | Elimina l'opzione in base al nome. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Rimuove questo campo e ne inserisce il valore direttamente nella pagina. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Restituisce l'enumeratore dei campi contenuti. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Restituisce il rettangolo di annotazione tenendo conto della rotazione della pagina. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Rielabora tutti i campi calcolati nel modulo. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Imposta la posizione del campo. |

### Guarda anche

* class [Field](../field)
* spazio dei nomi [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
