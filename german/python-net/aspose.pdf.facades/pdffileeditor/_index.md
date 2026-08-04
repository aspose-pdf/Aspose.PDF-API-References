---
title: "PdfFileEditor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Implementiert Vorgänge mit PDF-Datei-Konkatenation, Aufteilung, Extrahieren von Seiten, Erstellen von Heften usw."
type: docs
weight: 220
url: /de/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implementiert Operationen mit PDF‑Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen von Broschüren usw.

Der Typ PdfFileEditor stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileEditor() | Initialisiert eine neue Instanz der Klasse PdfFileEditor |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| conversion_log | Liefert das Protokoll des Konvertierungsprozesses. |
| merge_duplicate_layers | Optionale Inhalte von zusammengefügten Dokumenten mit gleichen Namen werden zu einer Ebene im Ergebnisdokument zusammengeführt, wenn diese Eigenschaft true ist. <br/>            Andernfalls werden Ebenen mit gleichen Namen als verschiedene Ebenen im Ergebnisdokument gespeichert. |
| copy_outlines | Wenn true, werden die Outlines kopiert. |
| copy_logical_structure | Wenn true, wird die logische Struktur der Datei beim Zusammenführen kopiert. |
| merge_duplicate_outlines | Wenn true, werden doppelte Outlines zusammengeführt. |
| preserve_user_rights | Wenn true, werden die Benutzerrechte des ersten Dokuments auf das zusammengeführte Dokument angewendet. Benutzerrechte aller anderen Dokumente werden ignoriert. |
| incremental_updates | Wenn true, werden während des Zusammenführens inkrementelle Updates durchgeführt. |
| optimize_size | Liest oder setzt das Optimierungsflag. Gleichwertige Ressourcenströme in der resultierenden Datei werden zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. <br/>            Dadurch kann die resultierende Dateigröße verringert werden, jedoch kann die Ausführung langsamer sein und ein höherer Speicherbedarf entstehen.<br/>            Standardwert: false. |
| corrupted_items | Array von aufgetretenen Problemen, wenn das Zusammenführen durchgeführt wurde. Für jedes beschädigte Dokument, das an Concatenate() übergeben wurde, <br/>            wird ein neuer Eintrag vom Typ CorruptedItem erstellt.<br/>            Diese Eigenschaft darf nur verwendet werden, wenn CorruptedFileAction den Wert ConcatenateIgnoringCorrupted hat. |
| corrupted_file_action | Diese Eigenschaft definiert das Verhalten, wenn der Zusammenführungsprozess auf eine beschädigte Datei trifft.<br/>            Mögliche Werte sind: StopWithError und ConcatenateIgnoringCorrupted. |
| owner_password | Legt das Passwort des Besitzers fest, falls die Quell‑Pdf‑Datei verschlüsselt ist.<br/>            Diese Eigenschaft ist noch nicht implementiert. |
| allow_concatenate_exceptions | Wenn auf true gesetzt, werden Ausnahmen ausgelöst, wenn ein Fehler auftritt. Andernfalls werden keine Ausnahmen ausgelöst und die Methoden geben false zurück, wenn sie fehlschlagen. |
| close_concatenated_streams | Wenn auf true gesetzt, werden die Streams nach dem Vorgang geschlossen. |
| unique_suffix | Format des Suffixes, das dem Feldnamen hinzugefügt wird, um ihn eindeutig zu machen, wenn Formulare zusammengeführt werden.<br/>            Dieser String muss das Teilzeichen %NUM% enthalten, das durch Zahlen ersetzt wird.<br/>            Beispiel: Wenn UniqueSuffix = "ABC%NUM%" ist, dann werden für das Feld "fieldName" die Namen erzeugt:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 usw. |
| keep_actions | Wenn true, werden Aktionen aus den Quelldokumenten kopiert. Standardwert: true. |
| keep_fields_unique | Wenn true, werden Feldnamen eindeutig gemacht, wenn Formulare zusammengeführt werden.<br/>            Suffixe werden zu Feldnamen hinzugefügt, das Suffix‑Template kann in der Eigenschaft UniqueSuffix angegeben werden. |
| remove_signatures | Wenn true, werden alle Signaturen aus den Feldern entfernt (die Felder bleiben erhalten); andernfalls können ungültige Signaturen entstehen. |
| use_disk_buffer | Wenn diese Option verwendet wird, wird das Zieldokument periodisch auf der Festplatte gespeichert und weitere Zusammenführungen werden als inkrementelle Updates darauf angewendet. |
| concatenation_packet_size | Anzahl der Dokumente, die zusammengeführt werden, bevor während der Zusammenführung ein neues inkrementelles Update erstellt wird, wenn UseDiskBuffer auf true gesetzt ist. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Führt zwei Dateien zusammen. |
| try_concatenate(src, dest) | Führt Dokumente zusammen. |
| try_concatenate(input_files, output_file) | Führt Dateien zu einer Datei zusammen. |
| try_concatenate(input_stream, output_stream) | Führt Dateien zusammen |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Führt zwei Dateien zusammen. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Führt Dateien zusammen |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Fügt Seiten hinzu, die aus dem Array von Dokumenten in portStreams ausgewählt werden.<br/>            Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams‑Dokumente im Bereich startPage bis endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Fügt Seiten hinzu, die aus den portFiles‑Dokumenten ausgewählt werden. <br/>            Das Ergebnisdokument enthält firstInputFile und alle Seiten der portFiles‑Dokumente im Bereich startPage bis endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Fügt Seiten aus einer anderen Datei in die Eingabe‑Pdf‑Datei ein. |
| try_delete(input_file, page_number, output_file) | Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue Pdf-Datei. |
| try_delete(input_stream, page_number, output_stream) | Löscht Seiten, die durch ein Zahlenarray angegeben sind, aus der Eingabedatei und speichert sie als neue Pdf-Datei. |
| try_extract(input_file, start_page, end_page, output_file) | Extrahiert Seiten aus der Eingabedatei und speichert sie als neue Pdf-Datei. |
| try_extract(input_file, page_number, output_file) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei. |
| try_extract(input_stream, page_number, output_stream) | Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue Pdf-Datei. |
| try_split_from_first(input_file, location, output_file) | Teilt die Pdf-Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei. |
| try_split_from_first(input_stream, location, output_stream) | Teilt von Anfang bis zum angegebenen Ort und speichert den vorderen Teil im output Stream. |
| try_split_to_end(input_file, location, output_file) | Teilt ab dem Ort und speichert den hinteren Teil als neue Datei. |
| try_split_to_end(input_stream, location, output_stream) | Teilt ab dem angegebenen Ort und speichert den hinteren Teil als neuen Datei Stream. |
| try_make_booklet(input_file, output_file) | Erstellt ein Booklet aus der Eingabedatei zur Ausgabedatei. |
| try_make_booklet(input_stream, output_stream) | Erstellt ein Booklet aus dem InputStream zum outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Erstellt ein Booklet aus der inputFile zur outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Erstellt ein Heft aus dem Eingabestream und speichert das Ergebnis in den Ausgabestream. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Erstellt ein benutzerdefiniertes Heft von firstInputFile nach outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Erstellt ein benutzerdefiniertes Heft von firstInputStream nach outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Erstellt ein benutzerdefiniertes Heft von firstInputFile nach outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Erstellt ein Heft von firstInputStream nach outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Erstellt ein N-Up-Dokument von firstInputFile nach outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis in den Ausgabestream. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Erstellt ein N-Up-Dokument vom ersten Eingabestream zum Ausgabestream. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Erstellt ein N-Up-Dokument von firstInputFile nach outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis in den Ausgabestream. |
| try_make_n_up(input_files, output_file, is_sidewise) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien zu outputFile. <br/>            Jede Seite von outputFile wird mehrere Seiten enthalten, die mit den Seiten <br/>            in den Eingabedateien derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt <br/>            wenn isSidewise true ist und vertikal gestapelt, wenn isSidewise false ist. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams zu outputStream.<br/>            Jede Seite von outputStream wird mehrere Seiten enthalten, die mit den Seiten <br/>            in den Eingabestreams derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt <br/>            wenn isSidewise true ist und vertikal gestapelt, wenn isSidewise false ist. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Erstellt ein N-Up-Dokument aus der Eingabedatei zu outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Ändert die Größe des Inhalts von Seiten des Dokuments. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Ändert die Größe des Inhalts von Dokumentseiten. <br/>            Verkleinert den Inhalt der Seite und fügt Ränder hinzu.<br/>            Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. |
| try_resize_contents(source, destination, pages, parameters) | Ändert die Größe des Inhalts von Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. |
| concatenate(first_input_file, sec_input_file, output_file) | Verkettet Dateien und speichert das Ergebnis in ein HttpResposnse-Objekt. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Verkettet Dateien und speichert das Ergebnis im HttpResponse-Objekt. |
| concatenate(src, dest) | Führt Dokumente zusammen. |
| concatenate(input_files, output_file) | Verkettet Dateien und speichert das Ergebnis in ein HttpResposnse-Objekt. |
| concatenate(input_stream, output_stream) | Verkettet Dateien und speichert das Ergebnis im HttpResponse-Objekt. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Verkettet Dateien und speichert das Ergebnis in ein HttpResposnse-Objekt. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Verkettet Dateien und speichert das Ergebnis im HttpResponse-Objekt. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Fügt Dokumente zum Quell‑Dokument hinzu und speichert das Ergebnis im response‑Objekt. |
| append(input_file, port_files, start_page, end_page, output_file) | Fügt Dokumente zum Quell‑Dokument hinzu und speichert das Ergebnis im HttpResponse-Objekt. |
| append(input_file, port_file, start_page, end_page, output_file) | Fügt Dokumente zum Quell‑Dokument hinzu und speichert das Ergebnis im HttpResponse-Objekt. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Fügt Dokumente zum Quell‑Dokument hinzu und speichert das Ergebnis im response‑Objekt. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Fügt den Inhalt einer Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis im response‑Objekt. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Fügt den Inhalt einer Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis im response‑Objekt. |
| delete(input_file, page_number, output_file) | Löscht angegebene Seiten aus dem Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| delete(input_stream, page_number, output_stream) | Löscht die angegebenen Seiten aus dem Dokument und speichert das Ergebnis in einem HttpResponse-Objekt. |
| extract(input_file, start_page, end_page, output_file) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis in einem HttpResponse-Objekt. |
| extract(input_file, page_number, output_file) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis in einem HttpResponse-Objekt. |
| extract(input_stream, start_page, end_page, output_stream) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis in einem HttpResponse-Objekt. |
| extract(input_stream, page_number, output_stream) | Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis in einem HttpResponse-Objekt. |
| split_from_first(input_file, location, output_file) | Teilt das Dokument von der ersten Seite bis zum angegebenen Ort und speichert das Ergebnis in HttpResponse-Objekten. |
| split_from_first(input_stream, location, output_stream) | Teilt das Dokument vom Anfang bis zum angegebenen Ort und speichert das Ergebnis in einem HttpResponse-Objekt. |
| split_to_end(input_file, location, output_file) | Teilt ab dem angegebenen Ort und speichert den hinteren Teil in einem HttpResponse-Objekt. |
| split_to_end(input_stream, location, output_stream) | Teilt ab dem angegebenen Ort und speichert den hinteren Teil in einem HttpResponse-Objekt. |
| make_booklet(input_file, output_file) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| make_booklet(input_stream, output_stream) | Erstellt ein Heft aus einer PDF-Datei und speichert es in einem HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| make_booklet(input_stream, output_stream, page_size) | Erstellt ein Heft aus einer PDF-Datei und speichert es in einem HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Erstellt ein Heft aus einer PDF-Datei und speichert es in einem HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Erstellt ein Heft aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Erstellt ein Heft aus einer PDF-Datei und speichert es in einem HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| make_n_up(input_stream, output_stream, x, y) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| make_n_up(first_input_file, second_input_file, output_file) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| make_n_up(input_files, output_file, is_sidewise) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien zu outputFile. <br/>            Jede Seite von outputFile wird mehrere Seiten enthalten, die mit den Seiten <br/>            in den Eingabedateien derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt <br/>            wenn isSidewise true ist und vertikal gestapelt, wenn isSidewise false ist. |
| make_n_up(input_streams, output_stream, is_sidewise) | Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams zu outputStream.<br/>            Jede Seite von outputStream wird mehrere Seiten enthalten, die mit den Seiten <br/>            in den Eingabestreams derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt <br/>            wenn isSidewise true ist und vertikal gestapelt, wenn isSidewise false ist. |
| make_n_up(input_file, output_file, x, y, page_size) | Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt. |
| split_to_pages(input_file, file_name_template) | Teilt die PDF-Datei in Einzelseiten-Dokumente auf. |
| split_to_pages(input_stream, file_name_template) | Teilt die PDF-Datei in Einzelseiten-Dokumente und speichert sie im angegebenen Pfad. Der Pfad wird durch das Feldnamen-Template angegeben. |
| resize_contents(source, destination, pages, parameters) | Ändert die Größe des Inhalts von Seiten im Dokument. Wenn eine Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert. |
| resize_contents(source, destination, pages, new_width, new_height) | Ändert die Größe des Inhalts von Dokumentseiten. <br/>            Verkleinert den Inhalt der Seite und fügt Ränder hinzu.<br/>            Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. |
| resize_contents(source, destination, pages, new_width, new_height) | Ändert die Größe des Inhalts von Dokumentseiten. <br/>            Verkleinert den Inhalt der Seite und fügt Ränder hinzu.<br/>            Die neue Größe des Inhalts wird in den standardmäßigen Raumeinheiten angegeben. |
| resize_contents(source, destination, pages, parameters) | Ändert die Größe des Inhalts von Seiten im Dokument. Wenn eine Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert. |
| resize_contents(source, pages, parameters) | Ändert die Größe der Seiten des Dokuments. Leere Ränder werden um die verkleinerte Seite herum hinzugefügt. |
| resize_contents(source, parameters) | Ändert die Größe der Seiten des Dokuments. Leere Ränder werden um die verkleinerte Seite herum hinzugefügt. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Ändert die Größe des Inhalts von Dokumentseiten.<br/>            Verkleinert den Seiteninhalt und fügt Ränder hinzu.<br/>            Die neue Inhaltsgröße wird in Prozent angegeben. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Ändert die Größe des Inhalts von Dokumentseiten.<br/>            Verkleinert den Seiteninhalt und fügt Ränder hinzu.<br/>            Die neue Inhaltsgröße wird in Prozent angegeben. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändert den Seiteninhalt und fügt angegebene Ränder hinzu. <br/>            Ränder werden in Standard‑Raumeinheiten angegeben. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändert den Seiteninhalt und fügt angegebene Ränder hinzu. <br/>            Ränder werden in Standard‑Raumeinheiten angegeben. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändert den Seiteninhalt und fügt die angegebenen Ränder hinzu.<br/>            Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Ändert den Seiteninhalt und fügt die angegebenen Ränder hinzu.<br/>            Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. |
| add_page_break(src, dest, page_breaks) | Fügt Seitenumbrüche in Dokumentseiten ein. |
| add_page_break(src, dest, page_breaks) | Fügt Seitenumbrüche in Dokumentseiten ein. |
| add_page_break(src, dest, page_breaks) | Fügt Seitenumbrüche in Dokumentseiten ein. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

