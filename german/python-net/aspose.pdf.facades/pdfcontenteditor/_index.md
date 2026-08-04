---
title: "PdfContentEditor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse dar, die den Inhalt von PDF‑Dateien bearbeitet."
type: docs
weight: 190
url: /de/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Stellt eine Klasse dar, die den Inhalt von PDF‑Dateien bearbeitet.

Der Typ PdfContentEditor stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfContentEditor() | Der Konstruktor des PdfContentEditor-Objekts. |
| PdfContentEditor(document) | Initialisiert eine neue Instanz der Klasse PdfContentEditor |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| text_search_options | Liest oder setzt Textsuchoptionen. |
| text_edit_options | Liest oder setzt Textbearbeitungsoptionen. |
| text_replace_options | Liest oder setzt Text-Ersetzungsoptionen. |
| replace_text_strategy | Ein Satz von Parametern für die Text-Ersetzungsoperation |
| DOCUMENT_OPEN | Ein Dokumentereignistyp. Öffnet ein Dokument. |
| DOCUMENT_CLOSE | Ein Dokumentereignistyp. Schließt ein Dokument. |
| DOCUMENT_WILL_SAVE | Ein Dokumentereignistyp. Führt eine Aktion vor dem Speichern aus. |
| DOCUMENT_SAVED | Ein Dokumentereignistyp. Führt eine Aktion nach dem Speichern aus. |
| DOCUMENT_WILL_PRINT | Ein Dokumentereignistyp. Führt eine Aktion vor dem Drucken aus. |
| DOCUMENT_PRINTED | Ein Dokumentereignistyp. Führt eine Aktion nach dem Drucken aus. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(input_file) | Bindet eine PDF-Datei zum Bearbeiten. |
| bind_pdf(input_stream) | Bindet einen PDF-Stream zum Bearbeiten. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das PDF-Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das PDF-Dokument in den angegebenen Stream. |
| create_web_link(rect, url, original_page, clr) | Erstellt einen Weblink im PDF-Dokument. |
| create_web_link(rect, url, original_page) | Erstellt einen Weblink im PDF-Dokument. |
| create_local_link(rect, des_page, original_page, clr) | Erstellt einen lokalen Link im PDF-Dokument. |
| create_local_link(rect, des_page, original_page) | Erstellt einen lokalen Link im PDF-Dokument. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Erstellt einen Link zu einer anderen Seite eines PDF-Dokuments. |
| create_application_link(rect, application, page, clr) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| create_application_link(rect, application, page) | Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument. |
| create_file_attachment(rect, contents, file_path, page, name) | Erstellt eine Dateianhang-Annotation. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Erstellt eine Dateianhang-Annotation. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Erstellt eine Dateianhang-Annotation. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Erstellt eine Dateianhang-Annotation. |
| add_document_attachment(file_attachment_path, description) | Fügt einen Dokumentenanhang ohne Annotation hinzu. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Fügt einen Dokumentenanhang ohne Annotation hinzu. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Erstellt eine Gummistempel-Anmerkung. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Erstellt eine Gummistempel-Anmerkung. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Erstellt eine Gummistempel-Anmerkung. |
| delete_image(page_number, index) | Löscht die angegebenen Bilder auf der angegebenen Seite. |
| delete_image() | Löscht die angegebenen Bilder auf der angegebenen Seite. |
| replace_text(src_string, the_page, dest_string, text_state) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Das [TextState](/pdf/python-net/aspose.pdf.text/textstate/)-Objekt (Schriftfamilie, Farbe) kann angegeben werden, um den Text zu ersetzen. |
| replace_text(src_string, dest_string) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Das [TextState](/pdf/python-net/aspose.pdf.text/textstate/)-Objekt (Schriftfamilie, Farbe) kann angegeben werden, um den Text zu ersetzen. |
| replace_text(src_string, the_page, dest_string) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Das [TextState](/pdf/python-net/aspose.pdf.text/textstate/)-Objekt (Schriftfamilie, Farbe) kann angegeben werden, um den Text zu ersetzen. |
| replace_text(src_string, dest_string, text_state) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Das [TextState](/pdf/python-net/aspose.pdf.text/textstate/)-Objekt (Schriftfamilie, Farbe) kann angegeben werden, um den Text zu ersetzen. |
| replace_text(src_string, dest_string, font_size) | Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Das [TextState](/pdf/python-net/aspose.pdf.text/textstate/)-Objekt (Schriftfamilie, Farbe) kann angegeben werden, um den Text zu ersetzen. |
| delete_stamp_by_ids(stamp_ids) | Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. |
| delete_stamp_by_ids(page_number, stamp_ids) | Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. |
| delete_stamp_by_id(page_number, stamp_id) | Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. |
| delete_stamp_by_id(stamp_id) | Löscht Stempel mit angegebenen IDs von allen Seiten des Dokuments. |
| close() | Schließt das geöffnete Dokument. |
| extract_link() | Extrahiert die Sammlung von Link-Instanzen, die im PDF-Dokument enthalten sind. |
| create_java_script_link(code, rect, original_page, color) | Erstellt einen Link zu JavaScript im PDF-Dokument. |
| create_text(rect, title, contents, open, icon, page) | Erstellt Textanmerkung im PDF-Dokument |
| create_free_text(rect, contents, page) | Erstellt Freitext-Anmerkung im PDF-Dokument |
| create_markup(rect, contents, type, page, clr) | Erstellt Markup-Anmerkung im PDF-Dokument. |
| create_popup(rect, contents, open, page) | Erstellt eine Popup-Annotation im PDF-Dokument. |
| delete_attachments() | Löscht alle Anhänge im PDF-Dokument. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Erstellt eine Linienannotation. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Erstellt eine Quadrat‑Kreis‑Annotation. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Erstellt eine Kurvenannotation. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Erstellt eine Polygon‑Annotation. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Erstellt eine Polylinien‑Annotation. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Erstellt eine Caret‑Annotation. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Erstellt ein Lesezeichen mit der angegebenen Aktion. |
| add_document_additional_action(event_type, code) | Fügt eine zusätzliche Aktion für das Dokumentenereignis hinzu. |
| remove_document_open_action() | Entfernt die Öffnungsaktion aus dem Dokument. Dieser Vorgang ist nützlich, wenn mehrere Dokumente zusammengeführt werden, die beim Start eine explizite 'GoTo'-Aktion verwenden. |
| change_viewer_preference(viewer_attribution) | Ändert die Ansichtseinstellung. |
| get_viewer_preference() | Gibt die Ansichtseinstellung zurück. |
| replace_image(page_number, index, image_file) | Ersetzt das angegebene Bild auf der angegebenen Seite des PDF-Dokuments durch ein anderes Bild. |
| create_movie(rect, file_path, page) | Erstellt Film-Anmerkungen. |
| create_sound(rect, file_path, name, page, rate) | Erstellt Sound-Anmerkungen. |
| delete_stamp(page_number, index) | Löscht mehrere Stempel auf der angegebenen Seite anhand von Stempelindizes. |
| hide_stamp_by_id(page_number, stamp_id) | Versteckt den Stempel. Nach dem Verstecken kann die Sichtbarkeit des Stempels mit der Methode ShowStampById wiederhergestellt werden. |
| show_stamp_by_id(page_number, stamp_id) | Zeigt den Stempel, der durch HiddenStampById versteckt wurde. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Ändert die Position des Stempels auf der Seite. |
| move_stamp(page_number, stamp_index, x, y) | Ändert die Position des Stempels auf der Seite. |
| get_stamps(page_number) | Gibt ein Array von Stempeln auf der Seite zurück. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

