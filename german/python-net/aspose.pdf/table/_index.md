---
title: "Tabelle"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann."
type: docs
weight: 1480
url: /de/python-net/aspose.pdf/table/
---

## Table class

Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann.

Der Tabellentyp stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Table() | Initialisiert eine neue Instanz der Klasse Tabelle |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Liest oder setzt die vertikale Ausrichtung eines Absatzes |
| horizontal_alignment | Liest oder setzt die horizontale Ausrichtung eines Absatzes |
| Rand | Liest oder setzt einen äußeren Rand für den Absatz (für die PDF-Erstellung) |
| is_first_paragraph_in_column | Liest oder setzt einen Bool-Wert, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_kept_with_next | Liest oder setzt einen Bool-Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_new_page | Liest oder setzt einen Bool-Wert, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_line_paragraph | Liest oder setzt, ob ein Absatz inline ist.<br/>            Standard ist false. (für die PDF-Erstellung) |
| Hyperlink | Liest oder setzt den Fragment-Hyperlink (für den PDF-Generator). |
| z_index | Liest oder setzt einen int‑Wert, der die Z‑Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex <br/>            wird über dem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem <br/>            ZIndex wird hinter dem Text auf der Seite platziert. |
| background_color | Liest oder setzt die Tabellenhintergrundfarbe |
| break_text | Liest oder setzt den Umbruchtext für die Tabelle |
| corner_style | Liest oder setzt die Stile der Rahmen-Ecken |
| repeating_rows_style | Liest den Stil für wiederholende Zeilen |
| repeating_columns_count | Liest oder setzt die maximale Spaltenanzahl für die Tabelle |
| repeating_rows_count | Liest die Anzahl der ersten Zeilen, die über mehrere Seiten wiederholt werden |
| column_widths | Liest die Spaltenbreiten der Tabelle. |
| broken | Liest oder setzt die vertikale Unterbrechung der Tabelle; |
| default_cell_border | Liest den Standardzellenrahmen; |
| default_column_width | Liest den Standardzellenrahmen; |
| Zeilen | Liest die Zeilen der Tabelle. |
| rahmen | Liest oder setzt den Rand. |
| default_cell_padding | Liest oder legt den Standardzellenabstand fest. |
| default_cell_text_state | Liest oder legt den Standard-Textzustand der Zelle fest. |
| ausrichtung | Liest oder setzt die Tabellenausrichtung. |
| left | Liest oder setzt die linke Koordinate der Tabelle. |
| top | Liest oder setzt die obere Koordinate der Tabelle. |
| is_broken | Liest oder legt fest, ob die Tabelle beschädigt ist – wird für die nächste Seite abgeschnitten. |
| is_borders_included | Liest oder legt fest, ob der Rand in die Spaltenbreiten einbezogen wird. |
| column_adjustment | Liest oder setzt die Spaltenanpassung der Tabelle. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Klonen Sie die Tabelle. |
| get_width() | Breite ermitteln. |
| get_height(parent_page) | Höhe ermitteln. |
| set_column_text_state(col_number, text_state) | Höhe festlegen. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Importiert ein eindimensionales Datenarray in die Tabelle. Der Import legt für jedes Element des Arrays eine Zelle an und<br/>              beginnt in der in den Parametern definierten Zeile und Spalte. Während des Imports wird, wenn festgestellt wird, dass notwendige Zeilen<br/>              noch fehlen (d. h. die Zieltabelle ist zu klein, um alle Daten aufzunehmen), die erforderlichen Zeilen erstellt. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

