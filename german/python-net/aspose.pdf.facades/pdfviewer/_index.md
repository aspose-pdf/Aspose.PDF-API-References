---
title: "PdfViewer"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse zum Anzeigen oder Drucken einer PDF-Datei dar."
type: docs
weight: 370
url: /de/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Stellt eine Klasse zum Anzeigen oder Drucken einer PDF-Datei dar.

Der PdfViewer-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfViewer() | Initialisiert ein neues [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) Objekt. |
| PdfViewer(document) | Initialisiert eine neue Instanz der PdfViewer-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| show_hidden_areas | Liest oder setzt das Flag, das die Sichtbarkeit versteckter Bereiche auf der Seite steuert. |
| print_status | Liest das Ergebnis des Druckauftrags. Bei Erfolg null; andernfalls ein Ausnahmeobjekt. |
| use_intermidiate_image | Liest/setzt die Verwendung der Konvertierung einer PDF-Seite in eine Zwischen‑PNG‑Datei während des Druckens im Dateimodus. Verwenden Sie dies, wenn die Größe der Ausgabedatei wichtig ist. |
| coordinate_type | Liest oder setzt den Seitenkoordinatentyp (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| print_as_image | Setzt oder liest einen Modus für PdfViewer, um als Bild zu drucken. |
| page_count | Liest die Seitenanzahl der aktuellen PDF-Datei. |
| password | Liest oder setzt das Passwort des Eingabedokuments. |
| print_page_dialog | Liest oder setzt einen booleschen Wert, der angibt, ob beim Drucken der Dialog zur Seitennummerierung angezeigt wird. |
| print_as_grayscale | Liest oder setzt einen booleschen Wert, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist er false. |
| printer_job_name | Liest oder setzt den Namen des Dokuments in der Druckwarteschlange, wenn das Dokument gedruckt wird. Der Standardwert ist der Dateiname. |
| form_presentation_mode | Liest oder setzt den Präsentationsmodus des Formulars. |
| rendering_options | Liest oder setzt die Rendering-Optionen. |
| vertical_alignment | Liest oder setzt einen Wert, der die vertikale Ausrichtung angibt |
| horizontal_alignment | Liest oder setzt einen Wert, der die horizontale Ausrichtung angibt |
| auto_resize | Liest oder setzt einen booleschen Wert, der angibt, ob die Datei mit optimierter Größe gedruckt werden soll. |
| auto_rotate | Liest oder setzt einen booleschen Wert, der angibt, ob die Datei mit automatischer Drehung gedruckt werden soll |
| auto_rotate_mode | Liest oder setzt einen AutoRotateMode-Wert, der die Drehrichtung angibt |
| resolution | Liest oder setzt die Auflösung beim Anzeigen und Drucken. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150. |
| scale_factor | Liest oder setzt einen Gleitkommawert, der den Skalierungsfaktor angibt. Der Standardwert ist 1,0. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| print_large_pdf(file_path) | Öffnet und druckt eine große PDF-Datei. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe <br/>             mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| print_large_pdf(input_stream) | Öffnet und druckt einen großen PDF-Stream. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr hat oder ihre Größe <br/>             mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| print_large_pdf(file_path, printer_settings) | Öffnet und druckt eine große PDF-Datei mit den angegebenen Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte <br/>             von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| print_large_pdf(input_stream, printer_settings) | Öffnet und druckt einen großen PDF-Stream mit den angegebenen Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte <br/>             von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. |
| print_large_pdf(file_path, page_settings, printer_settings) | Öffnet und druckt eine große PDF-Datei mit den angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF <br/>             Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um <br/>             eine bessere Leistung zu erzielen. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Öffnet und druckt einen großen PDF-Stream mit den angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF <br/>             Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um <br/>             eine bessere Leistung zu erzielen. |
| print_document_with_settings(page_settings, printer_settings) | Druckt das PDF-Dokument mit den Einstellungen. Wenn die Dokumentgröße nicht mit der Seitengröße kompatibel ist, wird pdf.kit sie erweitern, um zur Seitengröße zu passen. |
| print_document_with_settings(printer_settings) | Druckt das PDF-Dokument mit den Einstellungen. Wenn die Dokumentgröße nicht mit der Seitengröße kompatibel ist, wird pdf.kit sie erweitern, um zur Seitengröße zu passen. |
| open_pdf_file(file_path) | Öffnet eine PDF-Datei, dekodiert jedoch die Seiten der PDF-Datei nicht tatsächlich. |
| open_pdf_file(input_stream) | Öffnet einen PDF-Datei-Stream. Dekodiert jedoch die Seiten der PDF-Datei nicht tatsächlich. |
| bind_pdf(src_file) | Initialisiert die Fassade. |
| bind_pdf(src_stream) | Initialisiert die Fassade. |
| bind_pdf(src_doc) | Initialisiert die Fassade. |
| save(dest_file) | Speichert das resultierende PDF-Dokument in einer Datei. |
| save(dest_stream) | Speichert das resultierende PDF-Dokument in einen Stream. |
| decode_all_pages() | Liefert die Seiten der aktuellen PDF-Datei. |
| decode_page(page_number) | Dekodiert eine Seite einer PDF-Datei. |
| print_document_with_setup() | Druckt das PDF-Dokument mit einem Einrichtungsdialog. Wählen Sie einen Drucker über den Dialog aus. |
| print_document() | Druckt das PDF-Dokument mit einem Einrichtungsdialog. Wählen Sie einen Drucker über den Dialog aus. |
| get_default_page_settings() | Liefert die standardmäßigen Seiteneinstellungen. |
| get_default_printer_settings() | Liefert die standardmäßigen Druckereinstellungen. |
| close_pdf_file() | Schließt die aktuelle Pdf-Datei. |
| close() | Schließt die aktuelle Pdf-Datei. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

