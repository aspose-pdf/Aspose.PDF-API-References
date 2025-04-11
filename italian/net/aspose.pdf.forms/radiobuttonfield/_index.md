---
title: Class RadioButtonField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.RadioButtonField. Classe che rappresenta un campo di pulsante radio
type: docs
weight: 5210
url: /it/net/aspose.pdf.forms/radiobuttonfield/
---
## Classe RadioButtonField

Classe che rappresenta un campo di pulsante radio.

```csharp
public sealed class RadioButtonField : ChoiceField
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RadioButtonField](radiobuttonfield/#constructor)(Document) | Costruttore per RadioButtonField. |
| [RadioButtonField](radiobuttonfield/#constructor_1)(Page) | Costruttore per RadioButtonField |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Ottiene le azioni dell'annotazione. (2 proprietà) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Ottiene o imposta lo stato di apparizione corrente dell'annotazione. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Ottiene o imposta il nome alternativo del campo (Un nome di campo alternativo che deve essere utilizzato al posto del nome del campo effettivo ovunque il campo debba essere identificato nell'interfaccia utente). Il nome alternativo è utilizzato come tooltip del campo in Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Ottiene o imposta l'indice di questa annotazione sulla pagina. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Ottiene o imposta il flag di impegno al cambiamento di selezione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Ottiene il numero di sotto-campi in questo campo. (Ad esempio, il numero di elementi nel campo del pulsante radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ottiene o imposta l'apparenza predefinita del campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ottiene o imposta il flag esportabile del campo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ottiene il nome completamente qualificato dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Modalità di evidenziazione dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore di pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Ottiene o imposta un valore booleano che indica se questo campo è un campo non terminale, cioè un gruppo di campi. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore booleano che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione di pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Proprietà per il supporto del generatore. Utilizzato quando il campo è aggiunto all'intestazione o al piè di pagina. Se vero, questo campo sarà creato una sola volta e la sua apparizione sarà visibile su tutte le pagine del documento. Se falso, un campo separato sarà creato per ogni pagina del documento. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Restituisce vero se il dizionario è sincronizzato. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Ottiene il sotto-campo contenuto in questo campo per nome del sotto-campo. (2 indicizzatori) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Ottiene o imposta il nome di mapping del campo che deve essere utilizzato quando si esportano i dati del campo del modulo interattivo dal documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione di pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata recentemente modificata. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Ottiene o imposta il flag di multiselezione. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ottiene o imposta il nome dell'annotazione sulla pagina. |
| [NoToggleToOff](../../aspose.pdf.forms/radiobuttonfield/notoggletooff/) { get; set; } | Ottiene o imposta il flag che consente al pulsante radio di non avere un valore selezionato. Se `true`, esattamente un pulsante radio deve essere selezionato in ogni momento; selezionare il pulsante attualmente selezionato non ha effetto. Se `false`, cliccando sul pulsante selezionato lo deseleziona, lasciando nessun pulsante selezionato. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Un'azione che deve essere eseguita quando l'annotazione è attivata. |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options/) { get; } | Ottiene la collezione di opzioni del pulsante radio. |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex/) { get; } | Ottiene l'indice della pagina che contiene questo campo RadioButton. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ottiene il genitore dell'annotazione. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Ottiene o imposta il nome parziale del campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ottiene o imposta lo stato di sola lettura del campo. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Ottiene o imposta il rettangolo del campo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ottiene o imposta lo stato richiesto del campo. |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected/) { get; set; } | Ottiene o imposta l'indice dell'elemento selezionato. La numerazione degli elementi inizia da 1. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | Ottiene o imposta l'array degli elementi selezionati. Per l'elenco di multiselezione, l'array contiene più di un elemento. Per l'elenco di selezione singola, contiene un singolo elemento. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style/) { get; set; } | Stile della casella del campo. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Oggetto di sincronizzazione. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Ottiene o imposta l'ordine di tabulazione del campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value/) { get; set; } | Ottiene o imposta il valore del campo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accetta il visitatore. |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add/)(RadioButtonOptionField) | Aggiunge un nuovo campo opzione al campo RadioButton |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption)(string) | Aggiunge un'opzione al pulsante radio. |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption_1)(string, Rectangle) | Aggiunge un'opzione al pulsante radio con rettangolo specificato. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Aggiunge una nuova opzione con valore di esportazione e nome specificati. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aggiorna i parametri e l'apparenza, secondo la trasformazione della matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copia i sotto-campi di questo campo in un array a partire dall'indice specificato. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Elimina l'opzione per nome. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Esegue un'azione JavaScript specificata per il campo. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Esporta il campo del modulo PDF specificato in formato JSON e scrive il risultato nello stream fornito. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Esporta il campo del modulo PDF specificato in formato JSON e scrive il risultato nel file specificato. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Esporta il contenuto del campo specificato in uno stream JSON. I valori del campo pulsante non vengono esportati. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Rimuove questo campo e posiziona il suo valore direttamente sulla pagina. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Restituisce il nome dello stato "selezionato" secondo i nomi di stato esistenti. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Restituisce l'enumeratore dei campi contenuti. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importa i dati nei campi specificati da uno stream JSON, basandosi su una corrispondenza esatta dei nomi completi dei campi. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importa i dati nel campo specificato da uno stream JSON, utilizzando il nome completo specificato nella variabile 'fieldFullNameInJSON' per la corrispondenza. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Ricalcola tutti i campi calcolati nel modulo. |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition/)(Point) | Sposta tutti i sotto-elementi del pulsante radio nelle posizioni specificate sulla pagina. |

### Vedi Anche

* classe [ChoiceField](../choicefield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)