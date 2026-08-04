---
title: "PdfFileStamp"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien."
type: docs
weight: 320
url: /de/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien.

Der PdfFileStamp-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
| PdfFileStamp(input_stream, output_stream) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
| PdfFileStamp(input_file, output_file, keep_security) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
| PdfFileStamp(input_stream, output_stream, keep_security) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
| PdfFileStamp() | Konstruktor von PdfFileStamp.<br/>            Eingabedatei und Ausgabedatei können über die entsprechenden Eigenschaften angegeben werden. |
| PdfFileStamp(document) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
| PdfFileStamp(document, output_file) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
| PdfFileStamp(document, output_stream) | Initialisiert eine neue Instanz der PdfFileStamp-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| optimize_size | Liest oder setzt das Optimierungsflag. Gleichwertige Ressourcenströme in der resultierenden Datei werden zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. <br/>            Dadurch kann die resultierende Dateigröße verringert werden, jedoch kann die Ausführung langsamer sein und ein höherer Speicherbedarf entstehen.<br/>            Standardwert: false. |
| keep_security | Behält die Sicherheit bei, wenn true. (Dieses Feature wird in den nächsten Versionen implementiert.) |
| input_file | Liest oder setzt den Namen und Pfad der Eingabedatei. |
| input_stream | Liest oder setzt den Eingabestream. |
| output_file | Liest oder setzt den Namen und Pfad der Ausgabedatei. |
| output_stream | Liest oder setzt den Ausgabestream. |
| page_number_rotation | Liest oder setzt die Drehung der Seitenzahl. Die Drehung ist in Grad angegeben. Standard ist 0. |
| page_height | Liest die Höhe der ersten Seite in der Quellendatei. |
| page_width | Liest die Breite der ersten Seite in der Eingabedatei. |
| starting_number | Liest oder setzt die Startnummer für die erste Seite in der Eingabedatei. Folgende Seiten werden beginnend mit diesem Wert nummeriert. <br/>            Zum Beispiel, wenn StartingNumber auf 100 gesetzt ist, erhalten die Dokumentseiten die Nummern 100, 101, 102... |
| numbering_style | Liest oder setzt den Seitenzahl-Formatstil. Mögliche Werte: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | Stempel-ID des als Nächstes hinzugefügten Stempels (einschließlich Seitenkopfzeilen/ -fußzeilen/ Seitenzahlen). |
| POS_BOTTOM_MIDDLE | Untere mittlere Position. |
| POS_BOTTOM_RIGHT | Untere rechte Position. |
| POS_UPPER_RIGHT | Obere rechte Position. |
| POS_SIDES_RIGHT | Rechte Position. |
| POS_UPPER_MIDDLE | Obere mittlere Position. |
| POS_BOTTOM_LEFT | Untere linke Position. |
| POS_SIDES_LEFT | Linke Position. |
| POS_UPPER_LEFT | Obere linke Position. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das Ergebnis in die angegebene Datei. |
| save(dest_stream) | Speichert das Dokument in den angegebenen Stream. |
| add_page_number(format_string) | Fügt der Datei eine Seitenzahl hinzu. Der Text der Seitenzahl kann das Zeichen # enthalten, das durch die Seitennummer ersetzt wird. <br/>            Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. |
| add_page_number(formatted_text) | Fügt der Seite eine Seitenzahl hinzu. Die Seitenzahl kann das Zeichen # enthalten, das durch die Seitennummer ersetzt wird.<br/>            Die Seitenzahl wird am unteren Rand der Seite horizontal zentriert platziert. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Fügt dem Dokument Seitenzahlen zu den Seiten hinzu. |
| add_page_number(format_string, x, y) | Fügt dem Dokument Seitenzahlen zu den Seiten hinzu. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Fügt dem Dokument Seitenzahlen zu den Seiten hinzu. |
| add_page_number(formatted_text, x, y) | Fügt dem Dokument Seitenzahlen zu den Seiten hinzu. |
| add_page_number(format_string, position) | Fügt dem Dokument Seitenzahlen zu den Seiten hinzu. |
| add_page_number(formatted_text, position) | Fügt dem Dokument Seitenzahlen zu den Seiten hinzu. |
| add_header(formatted_text, top_margin) | Fügt der Seite eine Kopfzeile hinzu. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Fügt der Seite eine Kopfzeile hinzu. |
| add_header(image_file, top_margin) | Fügt dem Dokument ein Bild als Kopfzeile zu den Seiten hinzu. |
| add_header(image_file, top_margin, left_margin, right_margin) | Fügt dem Dokument ein Bild als Kopfzeile zu den Seiten hinzu. |
| add_header(image_stream, top_margin) | Fügt das Bild als Kopfzeile auf den Seiten hinzu. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Fügt das Bild als Kopfzeile auf den Seiten hinzu. |
| add_footer(formatted_text, bottom_margin) | Fügt eine Fußzeile zu den Seiten des Dokuments hinzu. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Fügt eine Fußzeile zu den Seiten des Dokuments hinzu. |
| add_footer(image_file, bottom_margin) | Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu. |
| add_footer(image_stream, bottom_margin) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Fügt ein Bild als Fußzeile der Seite hinzu. |
| close() | Schließt geöffnete Dateien und speichert Änderungen. <br/>            Warnung. Wenn Eingabe- oder Ausgabeströme angegeben sind, werden sie nicht von der Close()-Methode geschlossen. |
| add_stamp(stamp) | Fügt einen Stempel zur Datei hinzu. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

