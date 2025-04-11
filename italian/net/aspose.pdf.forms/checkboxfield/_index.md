---
title: Class CheckboxField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.CheckboxField. Classe che rappresenta un campo checkbox
type: docs
weight: 4980
url: /it/net/aspose.pdf.forms/checkboxfield/
---
## Classe CheckboxField

Classe che rappresenta un campo checkbox

```csharp
public class CheckboxField : Field
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CheckboxField](checkboxfield/#constructor_1)(Document) | Costruttore da utilizzare con il Generatore. |
| [CheckboxField](checkboxfield/#constructor_2)(Document, Rectangle) | Costruttore per la classe CheckboxField. |
| [CheckboxField](checkboxfield/#constructor_3)(Page, Rectangle) | Costruttore per la classe CheckboxField. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Ottiene le azioni dell'annotazione. (2 proprietà) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate/) { get; set; } | Ottiene o imposta lo stato di apparizione corrente dell'annotazione. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates/) { get; } | Restituisce l'elenco degli stati consentiti. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Ottiene o imposta il nome alternativo del campo (Un nome di campo alternativo che deve essere utilizzato al posto del nome effettivo del campo ovunque il campo debba essere identificato nell'interfaccia utente). Il nome alternativo è utilizzato come tooltip del campo in Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Ottiene o imposta l'indice di questa annotazione sulla pagina. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Ottiene il tipo di annotazione. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Ottiene le caratteristiche dell'annotazione. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked/) { get; set; } | Ottiene o imposta lo stato della casella di controllo. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Ottiene o imposta il colore dell'annotazione. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Ottiene o imposta il testo dell'annotazione. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Ottiene il numero di sottocampi in questo campo. (Ad esempio, il numero di elementi nel campo del pulsante di opzione). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Ottiene o imposta l'apparenza predefinita del campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Ottiene o imposta il flag esportabile del campo. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue/) { get; set; } | Ottiene o imposta il valore di esportazione del campo CheckBox. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flag dell'annotazione. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Ottiene il nome completamente qualificato dell'annotazione. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Ottiene o imposta l'altezza dell'annotazione. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Modalità di evidenziazione dell'annotazione. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è falso. (per la generazione pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Ottiene o imposta un valore booleano che indica se questo campo è un campo non terminale, cioè un gruppo di campi. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è falso. (per la generazione pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ottiene o imposta un valore bool che costringe questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è falso. (per la generazione pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è falso. (per la generazione pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Proprietà per il supporto del Generatore. Utilizzato quando il campo è aggiunto all'intestazione o al piè di pagina. Se vero, questo campo sarà creato una sola volta e la sua apparizione sarà visibile su tutte le pagine del documento. Se falso, un campo separato sarà creato per ogni pagina del documento. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Restituisce vero se il dizionario è sincronizzato. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Ottiene il sottocampo contenuto in questo campo per nome del sottocampo. (2 indicizzatori) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Ottiene o imposta il nome di mapping del campo che deve essere utilizzato quando si esportano i dati del campo del modulo interattivo dal documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ottiene o imposta un margine esterno per il paragrafo (per la generazione pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Ottiene o imposta la data e l'ora in cui l'annotazione è stata recentemente modificata. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Ottiene o imposta il nome dell'annotazione sulla pagina. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Un'azione che deve essere eseguita quando l'annotazione viene attivata. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Ottiene l'indice della pagina che contiene questo campo. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Ottiene il genitore dell'annotazione. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Ottiene o imposta il nome parziale del campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Ottiene o imposta lo stato di sola lettura del campo. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Ottiene o imposta il rettangolo del campo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Ottiene o imposta lo stato richiesto del campo. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Ottiene il dizionario di apparizione dell'annotazione. |
| [Style](../../aspose.pdf.forms/checkboxfield/style/) { get; set; } | Ottiene o imposta lo stile della casella di controllo. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Oggetto di sincronizzazione. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Ottiene o imposta l'ordine di tabulazione del campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value/) { get; set; } | Ottiene o imposta il valore del campo della casella di controllo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ottiene o imposta un allineamento verticale del paragrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Ottiene o imposta la larghezza dell'annotazione. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ottiene o imposta un valore int che indica l'ordine Z del grafico. Un grafico con un ZIndex maggiore sarà posizionato sopra il grafico con un ZIndex minore. ZIndex può essere negativo. Un grafico con ZIndex negativo sarà posizionato dietro il testo nella pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accetta il visitatore. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption)(string) | Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle di controllo può essere selezionata in qualsiasi momento. La nuova casella di controllo viene aggiunta in fondo al gruppo. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_1)(string, Rectangle) | Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle di controllo può essere selezionata in qualsiasi momento. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_2)(string, int, Rectangle) | Aggiunge una nuova casella di controllo a un gruppo di caselle di controllo, in cui al massimo una delle caselle di controllo può essere selezionata in qualsiasi momento. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Aggiorna i parametri e l'apparenza, secondo la trasformazione della matrice. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone/)() | Clona la casella di controllo. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copia i sottocampi di questo campo in un array a partire dall'indice specificato. |
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
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Ricalcola tutti i campi calcolati sul modulo. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Imposta la posizione del campo. |

## Esempi

L'esempio dimostra come creare un campo checkbox a più valori.

```csharp
using (var document = new Document())
{
var page = document.Pages.Add();

var checkbox = new CheckboxField(page, new Rectangle(50, 50, 70, 70));

// Set the first checkbox group option value
checkbox.ExportValue = "option 1";

// Add new option right under existing ones
checkbox.AddOption("option 2");

// Add new option at the given rectangle
checkbox.AddOption("option 3", new Rectangle(100, 100, 120, 120));

document.Form.Add(checkbox);

// Select the added checkbox
checkbox.Value = "option 2";
document.Save("checkbox_group.pdf");
}
```

### Vedi Anche

* classe [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)