---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSanitization. Rappresenta l'API di sanificazione e recupero. Usala se non puoi creare/aprire documenti in nessun altro modo
type: docs
weight: 4540
url: /it/net/aspose.pdf.facades/pdffilesanitization/
---
## Classe PdfFileSanitization

Rappresenta l'API di sanificazione e recupero. Usala se non puoi creare/aprire documenti in nessun altro modo.

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Dopo che il file è stato salvato, puoi controllare cosa è stato fatto con il file. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Consente di generare un nuovo xref e trailer per il documento. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Consente di rimuovere i dati dopo i dati pdf. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Consente di rimuovere i dati prima dei dati pdf. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Collega uno stream Pdf per la sanificazione. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Collega un file Pdf per la sanificazione. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Chiude la facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Rimuove il vecchio xref con trailer e crea un nuovo xref con trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Recupera il documento. Usa le proprietà per personalizzare. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Salva il PDF risultante nello stream. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Salva il PDF risultante nel file. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Rimuove i dati dopo l'ultimo %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Rimuove i dati prima di %PDF. |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)