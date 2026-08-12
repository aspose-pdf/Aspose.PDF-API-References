---
title: "Aspose::Pdf::Facades::PdfBookmarkEditor class"
linktitle: "PdfBookmarkEditor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfBookmarkEditor class. Representerar en klass för att arbeta med PDF-fils bokmärken inklusive skapa, modifiera, exportera, importera och radera i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class


Representerar en klass för att arbeta med PDF-filens bokmärken inklusive skapa, ändra, exportera, importera och ta bort.

```cpp
class PdfBookmarkEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::String\&, int32_t) | Skapar bokmärke för den angivna sidan. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<int32_t\>\&) | Skapar bokmärken för de angivna sidorna. |
| [CreateBookmarks](./createbookmarks/)() | Skapar bokmärken för alla sidor. |
| [CreateBookmarks](./createbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Skapar det angivna bokmärket i dokumentet. Metoden kan användas för att bilda en hierarki av nästlade bokmärken. |
| [CreateBookmarks](./createbookmarks/)(System::Drawing::Color, bool, bool) | Skapa bokmärken för alla sidor med angiven färg och stil (fet, kursiv). |
| [DeleteBookmarks](./deletebookmarks/)() | Raderar alla bokmärken i PDF-dokumentet. |
| [DeleteBookmarks](./deletebookmarks/)(const System::String\&) | Raderar bokmärket i PDF-dokumentet. |
| static [ExportBookmarksToHtml](./exportbookmarkstohtml/)(const System::String\&, const System::String\&) | Exporterar bokmärken till HTML-fil. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::String\&) | Exporterar bokmärken till XML-fil. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporterar bokmärken till XML-ström. |
| [ExtractBookmarks](./extractbookmarks/)() | Extraherar bokmärken på alla nivåer från dokumentet. |
| [ExtractBookmarks](./extractbookmarks/)(bool) | Extraherar bokmärken på alla nivåer från dokumentet. |
| [ExtractBookmarks](./extractbookmarks/)(const System::String\&) | Extraherar bokmärkena med den angivna titeln. |
| [ExtractBookmarks](./extractbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Extraherar underobjekten för ett bokmärke med en titel som i det angivna bokmärket. |
| [ExtractBookmarksToHTML](./extractbookmarkstohtml/)(const System::String\&, const System::String\&) | Exporterar bokmärken till HTML-fil. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::String\&) | Importerar bokmärken till dokumentet från en XML-fil. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar bokmärken till dokumentet från en XML-fil. |
| [ModifyBookmarks](./modifybookmarks/)(const System::String\&, const System::String\&) | Modifierar bokmärketitel enligt den angivna bokmärketiteln. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)() | Initierar ett nytt [PdfBookmarkEditor](./)-objekt. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfBookmarkEditor](./)-objekt baserat på *document*. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
