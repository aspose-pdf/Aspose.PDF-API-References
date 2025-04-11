---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor klass. Representerar en klass för att arbeta med PDF-filer bokmärken inklusive skapa, modifiera, exportera, importera och ta bort
type: docs
weight: 4420
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor klass

Representerar en klass för att arbeta med PDF-filers bokmärken inklusive skapa, modifiera, exportera, importera och ta bort.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Initierar ett nytt `PdfBookmarkEditor` objekt. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Initierar ett nytt `PdfBookmarkEditor` objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentets fasad som arbetas med. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Avsätter Aspose.Pdf.Document kopplad till en fasad. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Skapar bokmärke för den angivna sidan. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Skapar bokmärken för de angivna sidorna. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Skapar bokmärken för alla sidor. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Skapar det angivna bokmärket i dokumentet. Metoden kan användas för att bilda en hierarki av nästlade bokmärken. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Skapar bokmärken för alla sidor med angiven färg och stil (fet, kursiv). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Tar bort alla bokmärken från PDF-dokumentet. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Tar bort bokmärket från PDF-dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter fasaden. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Exporterar bokmärken till XML-ström. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Exporterar bokmärken till XML-fil. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Extraherar bokmärken av alla nivåer från dokumentet. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Extraherar barnen till ett bokmärke med en titel som i det angivna bokmärket. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Extraherar bokmärken av alla nivåer från dokumentet. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Extraherar bokmärken med den angivna titeln. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importerar bokmärken till dokumentet från XML-fil. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importerar bokmärken till dokumentet från XML-fil. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Modifierar bokmärkes titel enligt den angivna bokmärkes titeln. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Exporterar bokmärken till HTML-fil. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)