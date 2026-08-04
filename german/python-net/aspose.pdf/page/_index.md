---
title: "Page"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die eine Seite eines PDF-Dokuments darstellt."
type: docs
weight: 1080
url: /de/python-net/aspose.pdf/page/
---

## Page class

Klasse, die eine Seite eines PDF-Dokuments darstellt.

Der Typ Page stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_add_paragraphs_after_last | Liest oder setzt die Hinzufügung von Absätzen nach dem letzten Absatz der Seite |
| background_image | Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Einlesen des Dokuments nicht befüllt). |
| toc_info | Liest oder setzt Informationen zum Inhaltsverzeichnis. |
| header | Liest oder setzt die Seitenkopfzeile. |
| layers | Liest oder setzt die Ebenensammlung. |
| footer | Liest oder setzt die Seitenfußzeile. |
| paragraphs | Liest die Absätze. |
| page_info | Liest oder setzt die Seiteninformationen (nur für Generator, beim Lesen des Dokuments nicht gefüllt). |
| rechteck | Liest oder setzt das Rechteck der Seite.<br/>            Beim Lesen: Wird die Crop-Box der Seite zurückgegeben, falls angegeben, sonst wird die Media-Box der Seite zurückgegeben.<br/>            Beim Setzen: Wird immer die Media-Box der Seite gesetzt.<br/>            Bitte beachten Sie, dass diese Eigenschaft die Seitenrotation nicht berücksichtigt. Um das Seitenrechteck unter Berücksichtigung der Rotation zu erhalten, verwenden Sie bitte ActualRect. |
| color_type | Setzt den Farbtyp der Seiten basierend auf Informationen, die von den Operatoren SetColor,<br/>            Bildern und Formularen erhalten werden. |
| note_line_style | Liest oder setzt den Linienstil für Notizen (nur für Generator, beim Lesen des Dokuments nicht gefüllt). |
| tab_order | Liest oder setzt die Tab-Reihenfolge der Seite. <br/>            Mögliche Werte: Zeile, Spalte. Standard, Manuell |
| duration | Liest oder setzt die Anzeigedauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während einer Präsentation angezeigt werden soll.<br/>            Gibt -1 zurück, wenn keine Dauer definiert ist. |
| contents | Liest die Sammlung von Operatoren im Inhaltsstrom der Seite.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| group | Liest oder setzt eine Gruppenattributklasse, die die Attribute der Seiten‑Gruppierung für die Verwendung im transparenten Bildgebungsmodell angibt. |
| annotations | Liest die Sammlung von Seitenanmerkungen.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Liest die Seitenressourcen. Das Ressourcen‑Objekt enthält Sammlungen von Bildern, Formularen und Schriftarten.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| rotate | Liest oder setzt die Rotation der Seite. |
| trim_box | Liest oder setzt das trim box der Seite. |
| art_box | Liest oder setzt das art box der Seite. |
| bleed_box | Liest oder setzt das bleed box der Seite. |
| crop_box | Liest oder setzt das crop box der Seite. |
| media_box | Liest oder setzt das media box der Seite. |
| number | Erhalte die Seitennummer. |
| rotation_matrix | Liest die Transformationsmatrix für die Seite. |
| background | Liest oder setzt die Hintergrundfarbe der Seite. |
| watermark | Liest oder setzt das Wasserzeichen der Seite. |
| artifacts | Liest die Sammlung von Artefakten auf der Seite. |
| aktionen | Liest die Sammlung von Seiteneigenschaften. |
| fields_in_tab_order | Liest die Liste von Feldobjekten in Tab-Reihenfolge auf dieser Seite. |
| user_unit | Liest oder setzt den UserUnit-Wert. Eine positive Zahl, die die Größe der Standard‑Benutzerräumeinheiten in Vielfachen von 1 ⁄ 72 Zoll angibt.<br/>            Standardwert ist 1. Bitte setzen Sie Null oder einen negativen Wert, um diesen Eintrag auf der Seite zu löschen. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| send_to(device, output) | Sendet die Seite zur Verarbeitung mit dem angegebenen Page‑Device. |
| send_to(device, output_file_name) | Sendet die Seite zur Verarbeitung mit dem angegebenen Page‑Device. |
| accept(visitor) | Akzeptiert das [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) Besucherobjekt, das Funktionalität zum Arbeiten mit Anmerkungen bereitstellt. |
| accept(visitor) | Akzeptiert das [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| accept(visitor) | Akzeptiert das [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) Besucherobjekt, das Funktionalität zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| accept(visitor) | Akzeptiert das [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| add_image(image_stream, image_rect) | Fügt ein Bild auf die Seite ein und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Seitenverhältnis des Bildes beibehalten wird. |
| add_image(hocr, image_stream, image_rect) | Fügt ein durchsuchbares Bild auf die Seite ein und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Seitenverhältnis des Bildes beibehalten wird. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Fügt ein Bild auf der Seite ein und platziert es abhängig von der Position des Bildrechtecks. |
| add_image(image_path, rectangle) | Fügt ein durchsuchbares Bild auf die Seite ein und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Seitenverhältnis des Bildes beibehalten wird. |
| is_blank(fill_threshold_factor) | Ermittelt das Flag, ob die Seite leer ist oder nicht. |
| get_page_rect(consider_rotation) | Gibt das Rechteck der Seite gemäß ihrer CropBox zurück (oder MediaBox, falls CropBox null ist). |
| calculate_content_b_box() | Berechnet den BBox-Wert – das Rechteck, das den Inhalt ohne sichtbare Ränder enthält. |
| rotation_to_int(rotation) | Übersetzt das Rotations‑Enum‑Element in einen Ganzzahlwert. |
| int_to_rotation(rotation) | Übersetzt den Ganzzahlwert in das entsprechende Rotations‑Enum‑Element. |
| add_stamp(stamp) | Setzt einen Stempel auf die Seite. Der Stempel kann eine Seitenzahl, ein Bild oder einfacher Text sein, z. B. ein Logo. |
| flatten() | Entfernt alle auf der Seite befindlichen Felder und ersetzt sie durch deren Werte. |
| set_page_size(width, height) | Legt die Seitengröße fest. |
| make_grayscale() | Konvertiert die Seite in Graustufen. |
| free_memory() | Löscht zwischengespeicherte Daten |
| get_notifications() | Gibt Benachrichtigungen über interne Vorgänge mit dem Seiteninhalt zurück. (Derzeit werden nur Benachrichtigungen über Absatzereignisse in Text‑Hinzufügungs‑Szenarien unterstützt.) |
| as_byte_array(resolution) | Konvertiert die aktuelle Seite in ein Bitmap und gibt dann ein Byte-Array zurück. |
| as_xml() | Konvertiert die aktuelle Seite in XML mit UTF-8-Kodierung. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

