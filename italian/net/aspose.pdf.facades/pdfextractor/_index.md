---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfExtractor. Classe per estrarre immagini e testo da un documento PDF
type: docs
weight: 4450
url: /it/net/aspose.pdf.facades/pdfextractor/
---
## Classe PdfExtractor

Classe per estrarre immagini e testo da un documento PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Inizializza un nuovo oggetto `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfExtractor` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Ottiene o imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Imposta la modalità per il processo di estrazione delle immagini. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Imposta la modalità per il risultato dell'estrazione del testo. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | È vero quando il testo contiene simboli ebraici o arabi. Questo caso deve essere considerato in modo speciale perché le funzioni delle stringhe cambiano il loro comportamento e iniziano a elaborare il testo da destra a sinistra (eccetto numeri e altri caratteri non testuali). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Ottiene o imposta la password del file di input. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Imposta o ottiene la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con un valore di risoluzione maggiore sono più chiare. Tuttavia, l'aumento del valore di risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito, per ottenere un'immagine chiara è sufficiente impostare la risoluzione a 150 o 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Ottiene o imposta la pagina iniziale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Collega il documento PDF dallo stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Collega il file PDF di input. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Smaltisce Aspose.Pdf.Document collegato a una facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Estrae gli allegati da un documento Pdf. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Estrae un allegato da un file PDF in base al nome dell'allegato. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Estrae immagini da un file PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Estrae testo da un documento Pdf utilizzando la codifica Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Estrae testo da un documento Pdf utilizzando la codifica specificata. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Salva tutti i file di allegato negli stream. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Memorizza l'allegato in un file. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Ottiene l'elenco degli allegati. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Restituisce l'elenco degli allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Recupera la prossima immagine dal file PDF e la memorizza nello stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Recupera la prossima immagine dal documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Recupera la prossima immagine dal file PDF e la memorizza nello stream con il formato immagine dato. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Recupera la prossima immagine dal documento PDF con il formato immagine dato. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Salva il testo di una pagina nello stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Salva il testo di una pagina in un file. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Salva il testo nello stream. vedi anche:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Salva il testo in un file. vedi anche:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Salva il testo nello stream. vedi anche:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Controlla se ci sono altre immagini accessibili nel documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indica se è possibile ottenere più testi o meno. |

### Vedi anche

* classe [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)