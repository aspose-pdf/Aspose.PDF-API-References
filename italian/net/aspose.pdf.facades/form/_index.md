---
title: Form
second_title: Aspose.PDF per .NET API Reference
description: Classe che rappresenta loggetto modulo Acro.
type: docs
weight: 2300
url: /it/net/aspose.pdf.facades/form/
---
## Form class

Classe che rappresenta l'oggetto modulo Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Form](form#constructor)() | Costruttore di forme senza parametri. |
| [Form](form#constructor_1)(Document) | Inizializza nuovo[`Form`](../form) oggetto sulla base del*document* . |
| [Form](form#constructor_4)(Stream) | Costruttore per form. |
| [Form](form#constructor_8)(string) | Costruttore di Form. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | Ottiene o imposta il nome dell'allegato quando il risultato dell'operazione viene archiviato negli oggetti HttpResponse come allegato. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | Ottiene o imposta la modalità di archiviazione del contenuto quando il risultato dell'operazione viene archiviato nell'oggetto HttpResponse. Valore possibile: inline/allegato. Predefinito: inline. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | Imposta il formato del file PDF. Il file dei risultati verrà salvato nel formato file specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Ottiene l'elenco dei nomi dei campi nel modulo. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Ottiene tutti i nomi dei pulsanti di invio del modulo. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Risultato dell'ultima operazione di importazione. Array di oggetti che descrivono il risultato dell'importazione per ogni campo. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | Ottiene o imposta l'oggetto Response in cui verrà archiviato il risultato dell'operazione. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Ottiene o imposta le opzioni di salvataggio quando il risultato viene archiviato come HttpResponse. Valore predefinito: PdfSaveOptions. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inizializza la facciata. |
| override [Close](../../aspose.pdf.facades/form/close)() | Chiude i file aperti senza alcuna modifica. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | Esporta il contenuto dei campi del pdf nel flusso fdf. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo del pulsante non verrà esportato. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo del pulsante non verrà esportato. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | Estrae il pacchetto dati XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Compila un campo codice a barre in base al nome del campo completo. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Riempie il campo della casella di controllo con un valore booleano. Avviso: applicabile solo alla casella di controllo. Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali in contrasto con Aspose.Pdf .Kit; Ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al nome parziale. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Riempie il campo della casella radio con un valore di indice valido in base a un nome di campo completo. Prima di compilare i campi, è necessario conoscere solo il nome del campo. Sebbene il valore possa essere specificato dal relativo indice. Avviso: applicabile solo ai campi Radio Box, Combo Box e List Box. Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali in contrasto con Aspose.Pdf.Kit; Ad esempio se il campo ha il nome completo "Form.Subform.ListBoxField" è necessario specificare il nome completo e non "ListBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al nome parziale. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Riempie il campo con un valore valido in base a un nome di campo completo. Prima di compilare i campi, è necessario conoscere i nomi di ogni campo e i relativi valori validi corrispondenti. Sia il nome che i valori dei campi fanno distinzione tra maiuscole e minuscole. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali in contrasto con Aspose.Pdf.Kit; Ad esempio se il campo ha il nome completo "Form.Subform.TextField" è necessario specificare il nome completo e non "Campo di testo". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al nome parziale. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Compila un campo con selezioni multiple. Nota: solo per il campo Casella di riepilogo AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Riempie il campo con il valore specificato. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Riempie i campi della casella di testo con valori di testo e salva il documento. Rilevante per i documenti firmati. Avviso: applicabile solo alla casella di testo. Sia il nome che i valori dei campi fanno distinzione tra maiuscole e minuscole. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | Funzione di sovraccarico di FillImageField. L'input è un flusso di immagini. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Incolla un'immagine nel campo del pulsante esistente come aspetto in base a il nome del campo completo. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Appiattisce tutti i campi. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Unisce un campo specificato con il nome del campo completo. Qualsiasi altro campo rimarrà immodificabile. Se fieldName non è valido, tutti i campi rimarranno invariabili. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Restituisce il valore corrente per i campi delle opzioni dei pulsanti di opzione. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Ottiene i campi delle opzioni del pulsante di opzione e i valori correlati in base al nome del campo. Questo metodo ha significato per i gruppi di pulsanti di opzione. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Ottiene il valore del campo in base al nome del campo. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Restituisce l'oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Restituisce i flag del campo. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Ottieni la limitazione del campo di testo. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Restituisce il tipo di campo. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Ottiene il nome completo del campo in base al nome del campo breve. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Ottieni il valore di un campo Rich Text, incluse le informazioni sulla formattazione di ogni carattere. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Restituisce i flag di invio del pulsante di invio |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Importa il contenuto dei campi dal file fdf e li inserisce nel nuovo pdf. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Importa il contenuto dei campi dal file xfdf(xml) e li inserisce nel nuovo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Importa il contenuto dei campi dal file xml e li inserisce nel nuovo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Importa il contenuto dei campi dal file xml e li inserisce nel nuovo pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Determina se il campo è obbligatorio o meno. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Rinomina un campo. Il campo AcroForm o il campo XFA è OK. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Salva il documento nel flusso specificato. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Salva il documento nel file specificato. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | Sostituisce i dati XFA con il pacchetto di dati specificato. Il pacchetto di dati può essere estratto utilizzando ExtractXfaData. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Classe che descrive il risultato se il campo viene importato. |
| enum [ImportStatus](form.importstatus) | Stato del campo importato |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
