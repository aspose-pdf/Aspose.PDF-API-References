---
title: "Classe PdfFileSanitization"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Facades.PdfFileSanitization classe. Rappresenta l'API di sanificazione e recupero. Usala se non riesci a creare/aprire documenti in altro modo."
type: docs
weight: 4660
url: /it/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

Rappresenta l'API di sanificazione e recupero. Usala se non riesci a creare/aprire documenti in altro modo.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Dopo che il file è stato salvato, puoi verificare cosa è stato fatto al file. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Consente di generare un nuovo xref e trailer per il documento. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Consente di rimuovere i dati dopo i dati pdf. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Consente di rimuovere i dati prima dei dati pdf. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Inizializza il facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Associa un flusso Pdf per la sanificazione. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Associa un file Pdf per la sanificazione. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Chiude la facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Rimuove il vecchio xref con trailer e crea un nuovo xref con trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Recupera il documento. Usa le proprietà per personalizzare. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Salva il PDF risultante nello stream. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Salva il PDF risultante nel file. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Rimuove i dati dopo l'ultimo %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Rimuove i dati prima di %PDF. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


