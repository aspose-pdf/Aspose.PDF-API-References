---
title: "PdfFileMend"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse dar, die Texte und Bilder zu den Seiten eines bestehenden PDF‑Dokuments hinzufügt."
type: docs
weight: 280
url: /de/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Stellt eine Klasse dar, die Texte und Bilder zu den Seiten eines bestehenden PDF‑Dokuments hinzufügt.

Der Typ PdfFileMend stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileMend() | Konstruktor. |
| PdfFileMend(input_file_name, output_file_name) | Initialisiert eine neue Instanz der Klasse PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Initialisiert eine neue Instanz der Klasse PdfFileMend |
| PdfFileMend(document) | Initialisiert eine neue Instanz der Klasse PdfFileMend |
| PdfFileMend(document, output_file_name) | Initialisiert eine neue Instanz der Klasse PdfFileMend |
| PdfFileMend(document, dest_stream) | Initialisiert eine neue Instanz der Klasse PdfFileMend |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| input_stream | Setzt den Eingabestream. |
| output_stream | Setzt den Ausgabestream. |
| input_file | Setzt die Eingabedatei. |
| output_file | Setzt die Ausgabedatei. |
| wrap_mode | Legt den Zeilenumbruch-Algorithmus fest oder ruft ihn ab. Siehe WordWrapMode und IsWordWrap. |
| text_positioning_mode | Legt die Textpositionierungsstrategie fest oder ruft sie ab. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            Der Standardmodus ist Legacy. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das PDF-Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das PDF-Dokument in den angegebenen Stream. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Fügt ein Bild zur angegebenen Seite des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Fügt ein Bild zu den angegebenen Seiten des PDF-Dokuments an den angegebenen Koordinaten hinzu. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Nicht implementiert. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Nicht implementiert. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Nicht implementiert. |
| close() | Schließt das PdfFileMend-Objekt. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

