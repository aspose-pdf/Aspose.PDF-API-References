---
title: "Klass PdfBookmarkEditor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfBookmarkEditor-klass. Representerar en klass för att arbeta med PDF-fils bokmärken inklusive skapa, modifiera, exportera, importera och radera"
type: docs
weight: 4540
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

Representerar en klass för att arbeta med PDF file:s bokmärken inklusive skapa, ändra, exportera, importera och ta bort.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Initierar ett nytt `PdfBookmarkEditor`-objekt. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Initierar ett nytt `PdfBookmarkEditor`-objekt baserat på *document*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rensar Aspose.Pdf.Document som är bunden till en fasad. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Skapar bokmärke för den angivna sidan. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Skapar bokmärken för de angivna sidorna. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Skapar bokmärken för alla sidor. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Skapar det angivna bokmärket i dokumentet. Metoden kan användas för att bilda en hierarki av nästlade bokmärken. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Skapa bokmärken för alla sidor med angiven färg och stil (fet, kursiv). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Raderar alla bokmärken i PDF-dokumentet. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Raderar bokmärket i PDF-dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Exporterar bokmärken till XML-ström. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Exporterar bokmärken till en XML-fil. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Extraherar bokmärken på alla nivåer från dokumentet. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Extraherar underordnade till ett bokmärke med en titel som i det angivna bokmärket. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Extraherar bokmärken på alla nivåer från dokumentet. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Extraherar bokmärken med den angivna titeln. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importerar bokmärken till dokumentet från en XML-fil. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importerar bokmärken till dokumentet från en XML-fil. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Modifierar bokmärkestitel enligt den angivna bokmärkestiteln. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Exporterar bokmärken till en HTML-fil. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


