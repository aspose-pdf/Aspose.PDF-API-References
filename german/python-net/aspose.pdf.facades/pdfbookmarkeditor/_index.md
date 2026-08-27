---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse dar, die mit PDF‑Lesezeichen arbeitet, einschließlich Erstellen, Ändern, Exportieren, Importieren und Löschen."
type: docs
weight: 180
url: /de/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Stellt eine Klasse dar, die mit PDF‑Lesezeichen arbeitet, einschließlich Erstellen, Ändern, Exportieren, Importieren und Löschen.

Der PdfBookmarkEditor-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfBookmarkEditor() | Initialisiert ein neues [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) Objekt. |
| PdfBookmarkEditor(document) | Initialisiert eine neue Instanz der PdfBookmarkEditor-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das PDF-Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das PDF-Dokument in den angegebenen Stream. |
| create_bookmarks() | Erstellt Lesezeichen für alle Seiten. |
| create_bookmarks(bookmark) | Erstellt Lesezeichen für alle Seiten. |
| create_bookmarks(color, bold_flag, italic_flag) | Erstellt Lesezeichen für alle Seiten mit angegebener Farbe und Formatierung (fett, kursiv). |
| create_bookmark_of_page(bookmark_name, page_number) | Erstellt ein Lesezeichen für die angegebene Seite. |
| create_bookmark_of_page(bookmark_name, page_number) | Erstellt Lesezeichen für die angegebenen Seiten. |
| delete_bookmarks() | Löscht alle Lesezeichen des PDF-Dokuments. |
| delete_bookmarks(title) | Löscht das Lesezeichen des PDF-Dokuments. |
| extract_bookmarks() | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| extract_bookmarks(upper_level) | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| extract_bookmarks(title) | Extrahiert die Lesezeichen mit dem angegebenen Titel. |
| extract_bookmarks(bookmark) | Extrahiert Lesezeichen aller Ebenen aus dem Dokument. |
| export_bookmarks_to_xml(xml_file) | Exportiert Lesezeichen in eine XML-Datei. |
| export_bookmarks_to_xml(stream) | Exportiert Lesezeichen in einen XML-Stream. |
| import_bookmarks_with_xml(xml_file) | Importiert Lesezeichen in das Dokument aus einer XML-Datei. |
| import_bookmarks_with_xml(stream) | Importiert Lesezeichen in das Dokument aus einer XML-Datei. |
| close() | Gibt alle mit der aktuellen Fassade verbundenen Ressourcen frei. |
| modify_bookmarks(s_title, d_title) | Ändert den Lesezeichentitel gemäß dem angegebenen Lesezeichentitel. |
| extract_bookmarks_to_html(pdf_file, css_file) | Exportiert Lesezeichen in eine HTML-Datei. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Exportiert Lesezeichen in eine HTML-Datei. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

