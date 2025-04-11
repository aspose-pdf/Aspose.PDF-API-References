---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.Form. Classe che rappresenta l'oggetto Acro form
type: docs
weight: 4290
url: /it/net/aspose.pdf.facades/form/
---
## Classe Form

Classe che rappresenta l'oggetto Acro form.

```csharp
public sealed class Form : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Form](form/#constructor)() | Costruttore di Form senza parametri. |
| [Form](form/#constructor_1)(Document) | Inizializza un nuovo oggetto `Form` sulla base del *documento*. |
| [Form](form/#constructor_4)(Stream) | Costruttore per form. |
| [Form](form/#constructor_7)(string) | Costruttore di Form. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Imposta il formato del file PDF. Il file risultante sarà salvato nel formato di file specificato. Se questa proprietà non è specificata, il file sarà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Ottiene l'elenco dei nomi dei campi nel modulo. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Ottiene tutti i nomi dei pulsanti di invio del modulo. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Risultato dell'ultima operazione di importazione. Array di oggetti che descrivono il risultato dell'importazione per ciascun campo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Chiude i file aperti senza alcuna modifica. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Esporta il contenuto dei campi del pdf nello stream fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Esporta i contenuti di tutti i campi nel documento in uno stream JSON. I valori dei campi pulsante non vengono esportati. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non sarà esportato. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non sarà esportato. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Estrae il pacchetto di dati XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Compila un campo codice a barre secondo il suo nome di campo completamente qualificato. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Compila il campo della casella di controllo con un valore booleano. Nota: Applicabile solo alla casella di controllo. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField", è necessario specificare il nome completo e non "CheckBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al suo nome parziale. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Compila il campo della casella radio con un valore di indice valido secondo un nome di campo completamente qualificato. Prima di compilare i campi, deve essere noto solo il nome del campo. Mentre il valore può essere specificato dal suo indice. Nota: Applicabile solo ai campi della casella radio, della casella combinata e della casella elenco. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo "Form.Subform.ListBoxField", è necessario specificare il nome completo e non "ListBoxField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al suo nome parziale. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Compila il campo con un valore valido secondo un nome di campo completamente qualificato. Prima di compilare i campi, devono essere noti i nomi di tutti i campi e i loro valori validi corrispondenti. Sia i nomi dei campi che i valori sono sensibili al maiuscolo/minuscolo. Si prega di notare che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi di campo parziali, a differenza di Aspose.Pdf.Kit; Ad esempio, se il campo ha il nome completo "Form.Subform.TextField", è necessario specificare il nome completo e non "TextField". È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto in base al suo nome parziale. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Compila un campo con selezioni multiple. Nota: solo per il campo della casella elenco AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Compila il campo con il valore specificato. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Compila i campi della casella di testo con valori di testo e salva il documento. Rilevante per documenti firmati. Nota: Applicabile solo alla casella di testo. Sia i nomi dei campi che i valori sono sensibili al maiuscolo/minuscolo. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Sovraccarica la funzione di FillImageField. L'input è uno stream di immagine. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Incolla un'immagine sul campo pulsante esistente come sua apparenza secondo il suo nome di campo completamente qualificato. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Appiattisce tutti i campi. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Appiattisce un campo specificato con il nome di campo completamente qualificato. Qualsiasi altro campo rimarrà invariato. Se il fieldName è non valido, tutti i campi rimarranno invariati. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Restituisce il valore attuale per i campi delle opzioni dei pulsanti radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Ottiene i campi delle opzioni dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo ha significato per i gruppi di pulsanti radio. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Ottiene il valore del campo secondo il suo nome di campo. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Restituisce l'oggetto FrofmFieldFacade contenente tutti gli attributi di apparenza. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Restituisce i flag del campo. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Ottiene la limitazione del campo di testo. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Restituisce il tipo di campo. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Ottiene il nome completo del campo secondo il suo nome di campo breve. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Ottiene il valore di un campo di testo ricco, inclusa l'informazione di formattazione di ogni carattere. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Restituisce i flag di invio del pulsante di invio |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importa il contenuto dei campi dal file fdf e li inserisce nel nuovo pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importa tutti i dati dei campi da uno stream JSON nei campi del documento, abbinando i campi in base ai loro nomi completi. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importa il contenuto dei campi dal file xfdf(xml) e li inserisce nel nuovo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importa il contenuto dei campi dal file xml e li inserisce nel nuovo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importa il contenuto dei campi dal file xml e li inserisce nel nuovo pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Determina se il campo è obbligatorio o meno. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Rinomina un campo. È possibile utilizzare sia un campo AcroForm che un campo XFA. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Salva il documento nello stream specificato. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Salva il documento nel file specificato. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Sostituisce i dati XFA con il pacchetto di dati specificato. Il pacchetto di dati può essere estratto utilizzando ExtractXfaData. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Classe che descrive il risultato dell'importazione del campo. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Stato del campo importato |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)