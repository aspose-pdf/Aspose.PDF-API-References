---
title: "Classe PdfFileInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfFileInfo. Rappresenta una classe per accedere alle informazioni meta di PDF document"
type: docs
weight: 4640
url: /it/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Rappresenta una classe per accedere alle meta‑informazioni di un documento PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileInfo` sulla base del *document*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Ottiene o imposta le informazioni sull'autore di PDF document. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Ottiene o imposta le informazioni CreationDate di PDF document. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Ottiene o imposta le informazioni Creator di PDF document. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Restituisce true se il file di input corrente è un file 'Portfolio' che contiene una collezione di file PDF al suo interno. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Restituisce true se è necessaria una password per modificare le autorizzazioni o la proprietà di sicurezza del documento. Attenzione che questa proprietà può essere letta solo se è stata fornita una password valida nel costruttore `PdfFileInfo`. Nel caso in cui PasswordType sia Inaccessible (significa che è stata fornita una password non valida) la lettura di questa proprietà fallirà con [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Restituisce true se è necessaria una password per aprire un documento pdf protetto da password. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Ottiene o imposta le informazioni personalizzate di PDF document. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Verifica se il PDF document è crittografato. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Verifica se l'input di origine è un file PDF valido. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Ottiene o imposta le informazioni Keywords di PDF document. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Ottiene o imposta le informazioni ModDate di PDF document. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Ottiene il numero di pagine del document. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Restituisce il tipo di password che è stato passato per creare l'istanza PdfFileInfo. Vedi i possibili valori in [`PasswordType`](./passwordtype/). Attenzione che il pdf document può essere aperto sia con la password utente (o di apertura) sia con la password proprietario (o di autorizzazioni, modifica). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Ottiene le informazioni Producer di PDF document. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Ottiene o imposta le informazioni Subject di PDF document. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Ottiene o imposta le informazioni Title di PDF document. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Utilizza regole di validazione rigorose tramite l'uso della proprietà [`IsPdfFile`](./ispdffile/). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Inizializza il facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza il facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza il facade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Cancella tutte le informazioni meta del documento PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Deinizializza l'istanza. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Ottiene le impostazioni dei privilegi del documento PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Ottiene le informazioni personalizzate del documento PDF con il nome della proprietà. Se non esiste alcuna proprietà corrispondente al nome, restituisce una stringa vuota. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Ottiene l'altezza della pagina specificata. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Ottiene la rotazione della pagina specificata. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Ottiene la larghezza della pagina specificata. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Ottiene lo spostamento orizzontale dell'area di visualizzazione della pagina specificata. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Ottiene lo spostamento verticale dell'area di visualizzazione della pagina specificata. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Ottiene le informazioni sulla versione del documento PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Salva il documento PDF nel file specificato. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Salva il documento PDF nel file specificato. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Salva il documento PDF aggiornato nel file specificato. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Modifica le proprietà specificate esplicitamente impostando le informazioni del file, le altre proprietà rimangono. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Imposta le informazioni personalizzate del documento PDF. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


