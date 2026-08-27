---
title: "PdfExtractor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse zum Extrahieren von Bildern und Text aus PDF‑Dokumenten."
type: docs
weight: 210
url: /de/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Klasse zum Extrahieren von Bildern und Text aus PDF‑Dokumenten.

Der PdfExtractor-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfExtractor() | Initialisiert ein neues [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) Objekt. |
| PdfExtractor(document) | Initialisiert eine neue Instanz der PdfExtractor-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| start_page | Liest oder setzt die Startseite im Seitenbereich, in dem die Extraktionsoperation ausgeführt wird. |
| end_page | Liest oder setzt die Endseite im Seitenbereich, in dem die Extraktionsoperation ausgeführt wird. |
| extract_text_mode | Setzt den Modus für das Ergebnis der Textextraktion. |
| text_search_options | Liest oder setzt Textsuchoptionen. |
| extract_image_mode | Setzt den Modus für den Bildextraktionsprozess. |
| is_bidi | Ist wahr, wenn der Text hebräische oder arabische Symbole enthält. Dieser Fall muss besonders berücksichtigt werden, weil<br/>            String‑Funktionen ihr Verhalten ändern und den Text von rechts nach links verarbeiten (außer Zahlen <br/>            und anderen Nicht‑Text‑Zeichen). |
| resolution | Setzt oder liest die Auflösung für extrahierte Bilder.<br/>            Standardwert ist 150.<br/>            Bilder mit höherer Auflösung sind klarer.<br/>            Allerdings führt das Erhöhen der Auflösung zu mehr Zeit- und Speicheraufwand beim Extrahieren der Bilder.<br/>            In der Regel reicht es, die Auflösung auf 150 oder 300 zu setzen, um ein klares Bild zu erhalten. |
| password | Liest oder setzt das Passwort der Eingabedatei. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(input_file) | Bindet die Eingabe-PDF-Datei. |
| bind_pdf(input_stream) | Bindet das PDF-Dokument aus einem Stream. |
| bind_pdf(src_doc) | Initialisiert die Fassade. |
| extract_text() | Extrahiert Text aus einem PDF-Dokument unter Verwendung der Unicode-Kodierung. |
| extract_text(encoding) | Extrahiert Text aus einem PDF-Dokument mit der angegebenen Kodierung. |
| get_text(output_file) | Speichert Text in eine Datei. Siehe auch:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Speichert Text in einen Stream. Siehe auch:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Speichert Text in einen Stream. Siehe auch:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| get_next_image(output_file, format) | Ruft das nächste Bild aus dem PDF-Dokument im angegebenen Bildformat ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| get_next_image(output_stream, format) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es in einen Stream im angegebenen Bildformat. |
| get_next_image(output_stream) | Ruft das nächste Bild aus der PDF-Datei ab und speichert es in einen Stream im angegebenen Bildformat. |
| extract_attachment() | Extrahiert Anhänge aus einem PDF-Dokument. |
| extract_attachment(attachment_file_name) | Extrahiert einen Anhang aus der PDF-Datei anhand des Anhangsnamens. |
| get_next_page_text(output_file) | Speichert den Text einer Seite in eine Datei. |
| get_next_page_text(output_stream) | Speichert den Text einer Seite in einen Stream. |
| close() | Gibt Aspose.Pdf.Document frei, das mit einer Fassade verbunden ist. |
| extract_image() | Extrahiert Bilder aus einer PDF-Datei. |
| has_next_image() | Prüft, ob weitere Bilder im PDF-Dokument verfügbar sind. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden. |
| get_attach_names() | Gibt eine Liste der Anhänge in der PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden. |
| get_attachment(output_path) | Speichert den Anhang in einer Datei. |
| has_next_page_text() | Gibt an, ob weitere Texte abgerufen werden können oder nicht. |
| get_attachment_info() | Ruft die Liste der Anhänge ab. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

