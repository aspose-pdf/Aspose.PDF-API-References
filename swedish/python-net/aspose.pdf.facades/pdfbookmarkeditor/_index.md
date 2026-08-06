---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att arbeta med PDF‑filens bokmärken inklusive skapa, ändra, exportera, importera och ta bort."
type: docs
weight: 180
url: /sv/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Representerar en klass för att arbeta med PDF‑filens bokmärken inklusive skapa, ändra, exportera, importera och ta bort.

Typen PdfBookmarkEditor exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfBookmarkEditor() | Initierar ett nytt [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) objekt. |
| PdfBookmarkEditor(document) | Initierar en ny instans av klassen PdfBookmarkEditor |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar PDF-dokumentet till den angivna filen. |
| save(dest_stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| create_bookmarks() | Skapar bokmärken för alla sidor. |
| create_bookmarks(bookmark) | Skapar bokmärken för alla sidor. |
| create_bookmarks(color, bold_flag, italic_flag) | Skapa bokmärken för alla sidor med angiven färg och stil (fet, kursiv). |
| create_bookmark_of_page(bookmark_name, page_number) | Skapar ett bokmärke för den angivna sidan. |
| create_bookmark_of_page(bookmark_name, page_number) | Skapar bokmärken för de angivna sidorna. |
| delete_bookmarks() | Tar bort alla bokmärken i PDF-dokumentet. |
| delete_bookmarks(title) | Tar bort bokmärket i PDF-dokumentet. |
| extract_bookmarks() | Extraherar bokmärken på alla nivåer från dokumentet. |
| extract_bookmarks(upper_level) | Extraherar bokmärken på alla nivåer från dokumentet. |
| extract_bookmarks(title) | Extraherar bokmärken med den angivna titeln. |
| extract_bookmarks(bookmark) | Extraherar bokmärken på alla nivåer från dokumentet. |
| export_bookmarks_to_xml(xml_file) | Exporterar bokmärken till XML‑fil. |
| export_bookmarks_to_xml(stream) | Exporterar bokmärken till XML‑ström. |
| import_bookmarks_with_xml(xml_file) | Importerar bokmärken till dokumentet från XML‑fil. |
| import_bookmarks_with_xml(stream) | Importerar bokmärken till dokumentet från XML‑fil. |
| close() | Frigör alla resurser som är associerade med den aktuella fasaden. |
| modify_bookmarks(s_title, d_title) | Modifierar bokmärkestitel enligt den angivna bokmärkestiteln. |
| extract_bookmarks_to_html(pdf_file, css_file) | Exporterar bokmärken till HTML‑fil. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Exporterar bokmärken till HTML‑fil. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

