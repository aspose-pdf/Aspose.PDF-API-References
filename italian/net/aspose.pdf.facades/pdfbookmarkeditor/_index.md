---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfBookmarkEditor. Rappresenta una classe per lavorare con i segnalibri dei file PDF, inclusi creazione, modifica, esportazione, importazione e cancellazione
type: docs
weight: 4420
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## Classe PdfBookmarkEditor

Rappresenta una classe per lavorare con i segnalibri dei file PDF, inclusi creazione, modifica, esportazione, importazione e cancellazione.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Inizializza un nuovo oggetto `PdfBookmarkEditor`. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfBookmarkEditor` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facciata del documento su cui si sta lavorando. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rilascia Aspose.Pdf.Document legato a una facciata. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Crea un segnalibro per la pagina specificata. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Crea segnalibri per le pagine specificate. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Crea segnalibri per tutte le pagine. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Crea il segnalibro specificato nel documento. Il metodo può essere utilizzato per formare una gerarchia di segnalibri annidati. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Crea segnalibri per tutte le pagine con il colore e lo stile specificati (grassetto, corsivo). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Elimina tutti i segnalibri del documento PDF. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Elimina il segnalibro del documento PDF. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Esporta i segnalibri in un flusso XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Esporta i segnalibri in un file XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Estrae i segnalibri di tutti i livelli dal documento. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Estrae i figli di un segnalibro con un titolo simile a quello specificato. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Estrae i segnalibri di tutti i livelli dal documento. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Estrae i segnalibri con il titolo specificato. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importa i segnalibri nel documento da un file XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importa i segnalibri nel documento da un file XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Modifica il titolo del segnalibro secondo il titolo del segnalibro specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nel flusso specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Esporta i segnalibri in un file HTML. |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)