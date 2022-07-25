---
title: FormEditor
second_title: Aspose.PDF per .NET API Reference
description: Classe per la modifica dei moduli inserimento/cancellazione campo ecc.
type: docs
weight: 2340
url: /it/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Classe per la modifica dei moduli (inserimento/cancellazione campo ecc.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FormEditor](formeditor#constructor)() | Costruttore per FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | Inizializza nuovo[`FormEditor`](../formeditor) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | Ottiene o imposta il nome dell'allegato quando il risultato dell'operazione viene archiviato negli oggetti HttpResponse come allegato. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | Ottiene o imposta la modalità di archiviazione del contenuto quando il risultato dell'operazione viene archiviato nell'oggetto HttpResponse. Valore possibile: inline/allegato. Predefinito: inline. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | Imposta il formato del file PDF. Il file dei risultati verrà salvato nel formato file specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Imposta le opzioni per la casella combinata con i valori di esportazione. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Imposta gli attributi visivi del campo. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Imposta gli elementi che verranno aggiunti alla casella di riepilogo o alla casella combinata appena creata. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Ottiene o imposta la dimensione dell'elemento del pulsante di opzione (quando viene aggiunto un nuovo campo del pulsante di opzione). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | Il membro per registrare lo spazio tra due pulsanti di opzione adiacenti in pixel, il valore predefinito è 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | Il flag per indicare se le radio sono disposte orizzontalmente o verticalmente, il valore predefinito è true. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | Ottiene o imposta l'oggetto Response in cui verrà archiviato il risultato dell'operazione. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Ottiene o imposta le opzioni di salvataggio quando il risultato viene archiviato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Imposta i flag di invio del pulsante di invio |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Aggiungi il campo del tipo specificato al modulo. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Aggiungi il campo del tipo specificato al modulo. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Aggiungi JavaScript per un campo PushButton. Se il vecchio evento esiste, dopo di esso viene aggiunto il nuovo evento. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Aggiunge un nuovo elemento alla casella di riepilogo. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Aggiungi un nuovo elemento con il valore Esporta al campo della casella di riepilogo esistente, solo per il campo della casella combinata AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Aggiungi il pulsante di invio nel modulo. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inizializza la facciata. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Chiude la facciata. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Copia un campo esistente nella stessa posizione nel numero di pagina specificato. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento di origine ha ad eccezione del campo appena copiato. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina che dalle ordinate. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento di origine ha ad eccezione del campo appena copiato. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Copia un campo esistente da un documento PDF a un altro documento con numero di pagina e ordinate originali. Avviso: solo per i campi AcroForm (escluso il box radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le ordinate originali. Avviso: solo per i campi AcroForm (escluso il box radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le ordinate specificati. Avviso: solo per i campi AcroForm (escluso il box radio). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | Modifica gli attributi visivi di tutti i campi nel documento PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Modifica gli attributi visivi di tutti i campi con il tipo di campo specificato. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Modifica gli attributi visivi del campo specificato. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Elimina elemento dal campo elenco. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Ottieni flag di campo. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Imposta nuova posizione del campo. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Rimuovi campo dal modulo. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Rimuovi l'azione di invio del campo. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Modifica il nome del campo. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Reimposta tutti gli attributi visivi su un valore vuoto. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | Reimposta tutti gli attributi visivi della facciata interna su un valore vuoto. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Salva il documento PDF nel flusso specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Salva il documento PDF nel file specificato. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Imposta lo stile di allineamento di un campo di testo. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Imposta lo stile di allineamento verticale di un campo di testo. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Imposta flag di campo |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Imposta gli attributi del campo. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Imposta il numero di pettini per un normale campo di testo a riga singola (il campo è diviso automaticamente in tante posizioni equidistanti, o pettini, quanto il valore del parametro combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Imposta il numero massimo di caratteri del campo di testo. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | Imposta JavaScript per un campo PushButton. Se esisteva il vecchio JavaScript, verrà sostituito da quello nuovo. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Imposta il flag di invio del pulsante di invio. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Imposta l'URL del pulsante. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Modifica un campo di testo a riga singola in uno a più righe. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
