---
title: "PdfConverter"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse dar, die jede Seite einer Pdf-Datei in Bilder konvertiert und derzeit BMP, JPEG, PNG und TIFF unterstützt.<br/>            Unterstützte Inhalte in Pdfs sind Bilder, Formulare und Kommentare."
type: docs
weight: 200
url: /de/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Stellt eine Klasse dar, die jede Seite einer PDF‑Datei in Bilder konvertiert und derzeit BMP, JPEG, PNG und TIFF unterstützt.<br/>            Unterstützte Inhalte in PDFs: Bilder, Formulare, Kommentare.

Der PdfConverter-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfConverter() | Initialisiert ein neues [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) Objekt. |
| PdfConverter(document) | Initialisiert eine neue Instanz der PdfConverter-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| coordinate_type | Liest oder setzt den Seitenkoordinatentyp (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| show_hidden_areas | Liest oder setzt das Flag, das die Sichtbarkeit versteckter Bereiche auf der Seite steuert. |
| rendering_options | Liest oder setzt die Rendering-Optionen. |
| form_presentation_mode | Liest oder setzt den Präsentationsmodus des Formulars. |
| resolution | Liest oder setzt die Auflösung während der Konvertierung. Je höher die Auflösung, desto langsamer die Konvertierungsgeschwindigkeit. Der Standardwert ist 150. |
| start_page | Liest oder setzt die Startposition, die Sie konvertieren möchten. Der Minimalwert ist 1. |
| end_page | Liest oder setzt die Endposition, die Sie konvertieren möchten. |
| password | Liest oder setzt das Dokumenten‑OwnerPassword. |
| user_password | Liest oder setzt das Dokumenten‑UserPassword. |
| page_count | Liest die Seitenanzahl. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(input_file) | Bindet eine Pdf-Datei zum Konvertieren. |
| bind_pdf(input_stream) | Bindet einen PDF-Stream zum Konvertieren. |
| bind_pdf(src_doc) | Initialisiert die Fassade. |
| save_as_tiff(output_file) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, compression_type) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, image_width, image_height) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, page_size) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, page_size, settings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, image_width, image_height, settings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_stream) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| save_as_tiff(output_stream, compression_type) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_stream, page_size) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| save_as_tiff(output_stream, page_size, settings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzelnen TIFF-Stream. |
| save_as_tiff(output_stream, image_width, image_height) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| save_as_tiff(output_file, settings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_file, settings, converter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei. |
| save_as_tiff(output_stream, settings) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert die Bilder in einem einzelnen TIFF-Stream. |
| save_as_tiff(output_stream, settings, converter) | Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. |
| save_as_tiff_class_f(output_file, page_size) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| save_as_tiff_class_f(output_stream, page_size) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| save_as_tiff_class_f(output_file) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF ClassF-Datei. |
| save_as_tiff_class_f(output_stream) | Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF ClassF-Stream. |
| get_next_image(output_file) | Speichert das Bild in einer Datei mit dem Standardbildformat - jpeg. |
| get_next_image(output_file, page_size) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Standardbildformat - jpeg. |
| get_next_image(output_file, format) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat. |
| get_next_image(output_file, page_size, format) | Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Bildformat. |
| get_next_image(output_stream) | Speichert das Bild in einen Stream mit dem Standardbildformat - jpeg. |
| get_next_image(output_stream, page_size) | Speichert das Bild in einen Stream mit der angegebenen Seitengröße. |
| get_next_image(output_stream, format) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat. |
| get_next_image(output_stream, page_size, format) | Speichert das Bild in einen Stream mit der angegebenen Seitengröße. |
| get_next_image(output_file, format, image_width, image_height, quality) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| get_next_image(output_file, format, image_width, image_height, quality) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat, der Bildgröße und der Qualität. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, der Größe und der Qualität. |
| get_next_image(output_file, format, image_width, image_height) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| get_next_image(output_stream, format, image_width, image_height) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| get_next_image(output_stream, format, quality) | Speichert das Bild in einen Stream mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| get_next_image(output_stream, page_size, format, quality) | Speichert das Bild in einen Stream mit gegebener Seitengröße, Bildformat und Qualität. |
| get_next_image(output_file, format, quality) | Speichert das Bild in einer Datei mit dem angegebenen Bildformat, den Abmessungen und der Qualität. |
| get_next_image(output_file, page_size, format, quality) | Speichert das Bild in einer Datei mit gegebener Seitengröße, Bildformat und Qualität. |
| close() | Schließt die Instanz von PdfConverter und gibt die Ressourcen frei. |
| do_convert() | Führt einige anfängliche Arbeiten aus, um ein PDF-Dokument in Bilder zu konvertieren. |
| has_next_image() | Gibt an, ob die PDF-Datei weitere Bilder enthält oder nicht. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Keine |
| merge_images_as_tiff(input_images_streams) | Führt eine Liste von TIFF-Streams zu einem mehrframeigen TIFF-Stream zusammen. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

