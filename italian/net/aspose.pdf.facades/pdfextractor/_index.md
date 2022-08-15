---
title: PdfExtractor
second_title: Aspose.PDF per .NET API Reference
description: Classe per estrarre immagini e testo da documento PDF.
type: docs
weight: 2460
url: /it/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Classe per estrarre immagini e testo da documento PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Inizializza nuovo[`PdfExtractor`](../pdfextractor) oggetto. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Inizializza nuovo[`PdfExtractor`](../pdfextractor) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Ottiene o imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Imposta la modalità per il processo di estrazione delle immagini. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Imposta la modalità per estrarre il risultato del testo. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | È vero quando il testo ha simboli ebraici o arabi. Questo caso deve essere considerato in modo speciale perché le funzioni stringa cambiano il loro comportamento e avviano il processo di testo da destra a sinistra (tranne i numeri e altri caratteri non di testo). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Ottiene o imposta la password del file di input. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Imposta o ottiene la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con un valore di risoluzione maggiore sono più nitide. Tuttavia, l'aumento del valore della risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito per ottenere immagini nitide è sufficiente per impostare la risoluzione su 150 o 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Ottiene o imposta la pagina iniziale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Associa il documento PDF dallo stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | Associa file PDF di input. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Dispose Aspose.Pdf.Document rilegato con una facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Estrae gli allegati da un documento Pdf. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Estrae l'allegato al file PDF in base al nome dell'allegato. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | Estrai immagini da file PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Estrae il testo da un documento Pdf utilizzando la codifica Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Estrae il testo da un documento Pdf utilizzando la codifica specificata. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Salva tutti i file allegati negli stream. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Memorizza l'allegato nel file. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Ottiene l'elenco degli allegati. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | Restituisce l'elenco degli allegati nel file PDF. Nota: prima di utilizzare questo metodo è necessario chiamare ExtractAttachments. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | Recupera l'immagine successiva dal documento PDF. Nota: è necessario chiamare ExtractImage prima di utilizzare questo metodo. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Recupera l'immagine successiva dal documento PDF con il formato immagine specificato. Nota: è necessario chiamare ExtractImage prima di utilizzare questo metodo. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Salva il testo di una pagina in streaming. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Salva il testo di una pagina su file. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Salva il testo in streaming. Guarda anche:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Salva il testo su file. Guarda anche:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Salva il testo in streaming. Guarda anche:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | Verifica se più immagini sono accessibili nel documento PDF. Nota: è necessario chiamare ExtractImage prima di utilizzare questo metodo. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Indica se è possibile ottenere più testi o meno. |

### Guarda anche

* class [Facade](../facade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
