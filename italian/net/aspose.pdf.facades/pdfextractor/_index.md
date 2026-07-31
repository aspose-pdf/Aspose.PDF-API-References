---
title: "Classe PdfExtractor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Facades.PdfExtractor class. Classe per estrarre immagini e testo da un Pdf Document"
type: docs
weight: 4570
url: /it/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Classe per estrarre immagini e testo da un documento PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Inizializza un nuovo oggetto `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfExtractor` basato sul *Document*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Ottiene o imposta la Page finale nell'intervallo di Page in cui verrà eseguita l'operazione di estrazione. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Imposta la modalità per il processo di estrazione delle immagini. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Imposta la modalità per il risultato dell'estrazione del testo. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | È vero quando il testo contiene simboli ebraici o arabi. Questo caso deve essere considerato particolarmente perché le funzioni di stringa cambiano comportamento e avviano l'elaborazione del testo da destra a sinistra (eccetto numeri e altri caratteri non testuali). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Ottiene o imposta la password del file di input. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Imposta o ottiene la risoluzione per le immagini estratte. Il valore predefinito è 150. Le immagini con una risoluzione maggiore sono più nitide. Tuttavia aumentare la risoluzione comporta un aumento del tempo e della memoria necessari per estrarre le immagini. Di solito, per ottenere un'immagine nitida è sufficiente impostare la risoluzione a 150 o 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Ottiene o imposta la Page iniziale nell'intervallo di Page in cui verrà eseguita l'operazione di estrazione. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza il facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Associa il Document PDF dallo stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Associa il file PDF di input. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rilascia l'Aspose.Pdf.Document associato a una facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Estrae gli allegati da un Pdf Document. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Estrae l'allegato al file PDF per nome dell'allegato. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Estrai le immagini dal file PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Estrae il testo da un documento Pdf utilizzando la codifica Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Estrae il testo da un documento Pdf utilizzando la codifica specificata. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Salva tutti i file di allegato negli stream. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Memorizza l'allegato in un file. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Ottiene l'elenco degli allegati. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Restituisce l'elenco degli allegati nel file PDF. Nota: ExtractAttachments deve essere chiamato prima di utilizzare questo metodo. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Recupera l'immagine successiva dal documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Recupera l'immagine successiva dal documento PDF con il formato immagine specificato. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Salva il testo di una pagina nello stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Salva il testo di una pagina in un file. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Salva il testo nello stream. vedi anche:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Salva il testo in un file. vedi anche:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Salva il testo nello stream. vedi anche:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Verifica se sono disponibili altre immagini nel documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indica se è possibile ottenere più testi o meno. |

### Vedi anche

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


