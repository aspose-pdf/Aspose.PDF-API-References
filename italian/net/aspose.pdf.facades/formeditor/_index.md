---
title: "Classe FormEditor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.FormEditor. Classe per modificare i moduli aggiungendo/eliminando campi ecc"
type: docs
weight: 4450
url: /it/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Classe per modificare i moduli (aggiunta/cancellazione di campi ecc)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Costruttore per FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Inizializza un nuovo oggetto `FormEditor` basato sul *document*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Imposta le opzioni per la casella combinata con valori di esportazione. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Imposta gli attributi visivi del campo. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Imposta gli elementi che saranno aggiunti a una nuova casella di riepilogo o casella combinata. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Il flag per indicare se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Imposta i flag di invio del pulsante submit. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Aggiungi un campo del tipo specificato al modulo. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Aggiungi un campo del tipo specificato al modulo. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Aggiungi JavaScript per un campo PushButton. Se esiste un evento precedente, il nuovo evento viene aggiunto dopo di esso. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Aggiunge un nuovo elemento alla casella di riepilogo. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Aggiungi un nuovo elemento con valore Export al campo casella di riepilogo esistente, solo per il campo casella combinata AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Aggiungi un pulsante submit al modulo. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza il facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza il facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza il facade. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Chiude la facciata. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Copia un campo esistente nella stessa posizione del numero di pagina specificato. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento di origine possiede, eccetto il campo appena copiato. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina sia dalle coordinate. Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento di origine possiede, eccetto il campo appena copiato. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate originali. Nota: Solo per campi AcroForm (escluso radio box). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali. Nota: Solo per campi AcroForm (escluso radio box). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati. Nota: Solo per campi AcroForm (escluso radio box). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Modifica gli attributi visivi di tutti i campi nel documento PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Modifica gli attributi visivi di tutti i campi con il tipo di campo specificato. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Modifica gli attributi visivi del campo specificato. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Elimina l'elemento dal campo elenco. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Ottieni i flag del campo. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Imposta la nuova posizione del campo. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Rimuovi il campo dal modulo. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Rimuovi l'azione di invio del campo. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Cambia il nome del campo. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Reimposta tutti gli attributi visivi a valore vuoto. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Reimposta tutti gli attributi visivi della facciata interna a valore vuoto. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Imposta lo stile di allineamento di un campo di testo. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Imposta lo stile di allineamento verticale di un campo di testo. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Imposta i flag del campo |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Imposta gli attributi del campo. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Imposta il numero di combs per un campo di testo a riga singola regolare (il campo viene suddiviso automaticamente in tante posizioni equidistanti, o combs, quanto il valore del parametro combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Imposta il numero massimo di caratteri del campo di testo. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Imposta JavaScript per un campo PushButton. Se esisteva del JavaScript precedente, verrà sostituito da quello nuovo. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Imposta il flag di submit del pulsante submit. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Imposta l'URL del pulsante. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Modifica un campo di testo a riga singola in uno a più righe. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


