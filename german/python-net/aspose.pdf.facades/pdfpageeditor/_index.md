---
title: "PdfPageEditor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse zum Bearbeiten der Seiten einer PDF-Datei dar, einschließlich Drehen der Seite, Zoomen, Verschieben der Position und Ändern der Seitengröße."
type: docs
weight: 340
url: /de/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Stellt eine Klasse zum Bearbeiten der Seiten einer PDF-Datei dar, einschließlich Drehen der Seite, Zoomen, Verschieben der Position und Ändern der Seitengröße.

Der Typ PdfPageEditor stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfPageEditor() | Konstruktor für die Klasse PdfPageEditor. |
| PdfPageEditor(document) | Initialisiert eine neue Instanz der Klasse PdfPageEditor |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| transition_duration | Liest oder setzt die Dauer des Übergangseffekts. |
| transition_type | Liest oder setzt den Übergangsstil, der beim Wechsel zu dieser Seite von einer anderen während einer Präsentation verwendet wird. |
| display_duration | Liest oder setzt die Anzeigedauer für Seiten. |
| process_pages | Liest oder setzt die zu bearbeitenden Seitennummern. Standardmäßig wird jede Seite bearbeitet. |
| rotation | Liest oder setzt die Drehung der Seiten, die Drehung muss 0, 90, 180 oder 270 sein.<br/>            Standardwert ist 0. |
| zoom | Liest oder setzt den Zoomkoeffizienten. Wert 1.0 entspricht 100 %.<br/>            Standardwert ist 1.0. |
| page_size | Liest oder setzt die Seitengröße der Ausgabedatei. |
| ausrichtung | Liest oder setzt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist AlignmentType.Left. |
| horizontal_alignment | Liest oder setzt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist AlignmentType.Left. |
| vertical_alignment | Liest oder setzt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Liest oder setzt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist VerticalAlignmentType.Bottom. |
| SPLITVOUT | Vertikale Teilung nach außen |
| SPLITHOUT | Horizontale Teilung nach außen |
| SPLITVIN | Vertikale Teilung nach innen |
| SPLITHIN | Horizontale Teilung nach innen |
| BLINDV | Vertikale Jalousien |
| BLINDH | Vertikale Jalousien |
| INBOX | Innere Box |
| OUTBOX | Äußere Box |
| LRWIPE | Wisch von links nach rechts |
| RLWIPE | Wisch von rechts nach links |
| BTWIPE | Wisch von unten nach oben |
| TBWIPE | Wisch von oben nach unten |
| AUFLÖSEN | Die alte Seite löst sich auf |
| LRGLITTER | Glitzer von links nach rechts |
| TBGLITTER | Glitzer von oben nach unten |
| DGLITTER | Diagonaler Glitzer |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(output_file) | Speichert das geänderte Dokument in einer Datei. |
| save(output_stream) | Speichert das geänderte Dokument in einen Stream. |
| close() | Gibt alle mit der aktuellen Fassade verbundenen Ressourcen frei. |
| move_position(move_x, move_y) | Verschiebt den Ursprung von (0, 0) zu dem angegebenen Punkt. <br/>            Der Ursprung befindet sich links unten und die Einheit ist Punkt(1 Zoll = 72 Punkte). |
| get_pages() | Gibt die Gesamtzahl der Seiten zurück. |
| get_page_size(page) | Gibt die Seitengröße der angegebenen Seite zurück. |
| get_page_rotation(page) | Gibt die Drehung der angegebenen Seite zurück. |
| get_page_box_size(page, page_box_name) | Gibt die Größe des angegebenen Feldes im Dokument zurück. |
| apply_changes() | Wendet die an den Dokumentseiten vorgenommenen Änderungen an. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

