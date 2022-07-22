---
title: PdfFileInfo
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per laccesso alle metainformazioni del documento PDF.
type: docs
weight: 2530
url: /it/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Rappresenta una classe per l'accesso alle metainformazioni del documento PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | Inizializza nuovo[`PdfFileInfo`](../pdffileinfo) oggetto sulla base del*document* . |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | Ottiene o imposta le informazioni sull'autore del documento PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | Ottiene o imposta le informazioni CreationDate del documento PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | Ottiene o imposta le informazioni sull'autore del documento PDF. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | Restituisce true se il file di input corrente è un file 'Portfolio' contenente una raccolta di file PDF. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | Restituisce vero se la password è necessaria per modificare i permessi o la proprietà di sicurezza del documento. Prestare attenzione che questa proprietà può essere letta solo se è stata fornita una password valida in[`PdfFileInfo`](../pdffileinfo) costruttore. Nel caso in cui PasswordType sia inaccessibile (significa che è stata fornita una password non valida) la lettura di questa proprietà fallirà con[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception) . |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | Restituisce true se è necessaria la password per aprire il documento pdf protetto da password. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | Ottiene o imposta le informazioni personalizzate del documento PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | Verifica se il documento PDF è crittografato. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | Verifica se l'input di origine è un file PDF valido. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | Ottiene o imposta le informazioni sulle parole chiave del documento PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | Ottiene o imposta le informazioni sulla data ModDate del documento PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | Ottiene il numero di pagine del documento. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | Restituisce il tipo di password passato per la creazione dell'istanza PdfFileInfo. Vedi possibili valori in[`PasswordType`](./passwordtype) . Prestare attenzione che il documento pdf può essere aperto utilizzando sia la password utente (o apri) sia la password del proprietario (o autorizzazioni, modifica). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | Ottiene le informazioni sul produttore del documento PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | Ottiene o imposta le informazioni sull'oggetto del documento PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | Ottiene o imposta le informazioni sul titolo del documento PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | Utilizza regole di convalida rigorose tramite l'utilizzo[`IsPdfFile`](./ispdffile) proprietà. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inizializza la facciata. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | Cancella tutte le metainformazioni del documento PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | Deinizializza l'istanza. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | Ottiene le impostazioni dei privilegi del documento PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | Ottiene informazioni personalizzate del documento PDF con il nome della proprietà. Se nessuna proprietà corrisponde al nome, restituirà una stringa vuota. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | Ottiene l'altezza della pagina specificata. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | Ottiene la rotazione della pagina specificata. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | Ottiene la larghezza della pagina specificata. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | Ottiene l'offset orizzontale dell'area di visualizzazione della pagina specificata. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | Ottiene l'offset verticale dell'area di visualizzazione della pagina specificata. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | Ottiene le informazioni sulla versione del documento PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | Salva il documento PDF nel file specificato. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | Salva il documento PDF nel file specificato. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | Salva il documento PDF aggiornato nel file specificato. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | Modifica le proprietà specificate in modo esplicito impostando le informazioni sul file, le altre proprietà rimangono. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | Imposta le informazioni personalizzate del documento PDF. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
