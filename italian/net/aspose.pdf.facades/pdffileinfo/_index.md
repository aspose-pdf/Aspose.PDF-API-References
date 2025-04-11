---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileInfo. Rappresenta una classe per accedere alle informazioni meta del documento PDF
type: docs
weight: 4520
url: /it/net/aspose.pdf.facades/pdffileinfo/
---
## Classe PdfFileInfo

Rappresenta una classe per accedere alle informazioni meta del documento PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileInfo` basato sul *documento*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Ottiene o imposta le informazioni sull'autore del documento PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Ottiene o imposta le informazioni sulla data di creazione del documento PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Ottiene o imposta le informazioni sul creatore del documento PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Restituisce true se il file di input corrente è un file 'Portfolio' contenente una collezione di file PDF. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Restituisce true se è necessaria una password per modificare le autorizzazioni o la proprietà di sicurezza del documento. Fai attenzione che questa proprietà può essere letta solo se è stata fornita una password valida nel costruttore `PdfFileInfo`. Se il PasswordType è Inaccessible (significa che è stata fornita una password non valida), la lettura di questa proprietà fallirà con [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Restituisce true se è necessaria una password per aprire il documento PDF protetto da password. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Ottiene o imposta le informazioni personalizzate del documento PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Controlla se il documento PDF è crittografato. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Controlla se l'input sorgente è un file PDF valido. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Ottiene o imposta le informazioni sulle parole chiave del documento PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Ottiene o imposta le informazioni sulla data di modifica del documento PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Ottiene il numero di pagine del documento. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Restituisce il tipo di password che è stata fornita per creare l'istanza di PdfFileInfo. Vedi i valori possibili in [`PasswordType`](./passwordtype/). Fai attenzione che il documento PDF può essere aperto utilizzando sia la password utente (o di apertura) che la password proprietario (o di autorizzazioni, modifica). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Ottiene le informazioni sul produttore del documento PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Ottiene o imposta le informazioni sull'oggetto del documento PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Ottiene o imposta le informazioni sul titolo del documento PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Utilizza regole di validazione rigorose tramite l'uso della proprietà [`IsPdfFile`](./ispdffile/). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Pulisce tutte le informazioni meta del documento PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Deinizializza l'istanza. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Ottiene le impostazioni dei privilegi del documento PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Ottiene informazioni personalizzate del documento PDF con nome della proprietà. Se non c'è corrispondenza con il nome della proprietà, restituirà una stringa vuota. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Ottiene l'altezza della pagina specificata. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Ottiene la rotazione della pagina specificata. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Ottiene la larghezza della pagina specificata. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Ottiene l'offset orizzontale dell'area di visualizzazione della pagina specificata. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Ottiene l'offset verticale dell'area di visualizzazione della pagina specificata. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Ottiene le informazioni sulla versione del documento PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Salva il documento PDF nel file specificato. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Salva il documento PDF nel file specificato. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Salva il documento PDF aggiornato nel file specificato. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Modifica le proprietà specificate esplicitamente impostando le informazioni sul file, le altre proprietà rimangono. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Imposta informazioni personalizzate del documento PDF. |

### Vedi anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)