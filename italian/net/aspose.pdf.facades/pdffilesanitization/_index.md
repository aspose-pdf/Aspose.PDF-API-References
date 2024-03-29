---
title: PdfFileSanitization
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta lAPI di sanificazione e ripristino. Usalo se non puoi creare/aprire documenti in altro modo.
type: docs
weight: 2550
url: /it/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

Rappresenta l'API di sanificazione e ripristino. Usalo se non puoi creare/aprire documenti in altro modo.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log) { get; } | Dopo che il file è stato salvato, puoi controllare cosa è stato fatto con il file. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom) { get; set; } | Consente di rimuovere i dati dopo i dati pdf |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop) { get; set; } | Consente di rimuovere i dati prima dei dati pdf. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf#bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf#bindpdf_1)(Stream) | Associa un flusso Pdf per Sanitize. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf#bindpdf_2)(string) | Associa un file Pdf per Sanitize. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close)() | Chiude la facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover)() | Recupera il documento. Usa le proprietà per personalizzare. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save#save)(Stream) | Salva il risultato PDF in streaming. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save#save_1)(string) | Salva il risultato PDF su file. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom)() | Rimuove i dati dopo l'ultimo %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop)() | Rimuove i dati prima di %PDF. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
