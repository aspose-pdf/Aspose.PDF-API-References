---
title: "Field"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Basisklasse für Acro-Formularfelder."
type: docs
weight: 90
url: /de/python-net/aspose.pdf.forms/field/
---

## Field class

Basisklasse für Acro-Formularfelder.

Der Feldtyp stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Field(doc) | Initialisiert eine neue Instanz der Field-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Keine |
| horizontal_alignment | Liest oder setzt die Textausrichtung für die Anmerkung. |
| Rand | Keine |
| is_first_paragraph_in_column | Keine |
| is_kept_with_next | Keine |
| is_in_new_page | Keine |
| is_in_line_paragraph | Keine |
| Hyperlink | Keine |
| z_index | Keine |
| aktualisiere_erscheinung_beim_konvertieren | Wenn true, wird das Aussehen der Anmerkung aktualisiert, bevor das PF-Dokument in ein Bild konvertiert wird. Dies ermöglicht eine korrekte Konvertierung der Felder, kann jedoch wahrscheinlich mehr Zeit benötigen. |
| verwende_schriftart_teilmenge | Wenn diese Eigenschaft auf true gesetzt ist, werden Schriftarten dem Dokument als Teilmengen hinzugefügt. Der Standardwert ist true. |
| flaggen | Flags der Anmerkung. |
| anmerkung_typ | Ermittelt den Typ der Anmerkung. |
| breite | Liest oder setzt die Breite der Anmerkung. |
| aktionen | Ermittelt die Anmerkungsaktionen. |
| höhe | Liest oder setzt die Höhe der Anmerkung. |
| rechteck | Ermittelt oder setzt das Feldrechteck. |
| inhalt | Liest oder setzt den Anmerkungstext. |
| Name | Liest oder setzt den Anmerkungsnamen auf der Seite. |
| geändert | Liest oder setzt Datum und Uhrzeit, wann die Anmerkung zuletzt geändert wurde. |
| farbe | Liest oder setzt die Anmerkungsfarbe. |
| border | Liest oder setzt die Randmerkmale der Anmerkung. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| aktiver_zustand | Liest oder setzt den aktuellen Annotationsanzeigestatus. |
| eigenschaften | Liest die Anmerkungsmerkmale. |
| zustände | Liest das Erscheinungsdictionary der Anmerkung. |
| ausrichtung | Anmerkungs-Ausrichtung. Diese Eigenschaft ist veraltet. Verwenden Sie stattdessen HorizontalAligment. |
| text_horizontale_ausrichtung | Liest oder setzt die Textausrichtung für die Anmerkung. |
| vollständiger_name | Ermittelt den vollständig qualifizierten Namen der Anmerkung. |
| erscheinung | Ermittelt das Erscheinungsdictionary der Anmerkung. |
| seiten_index | Ermittelt den Index der Seite, die dieses Feld enthält. |
| bei_aktivierung | Eine Aktion, die ausgeführt werden soll, wenn die Anmerkung aktiviert wird. |
| Hervorhebung | Modus für Anmerkungs-Hervorhebung. |
| Eltern | Liefert den Elternteil der Anmerkung. |
| default_appearance | Liefert oder setzt das Standardaussehen des Feldes. |
| read_only | Liefert oder setzt den Nur-Lese-Status des Feldes. |
| required | Liefert oder setzt den Pflichtstatus des Feldes. |
| exportable | Liefert oder setzt das exportierbare Flag des Feldes. |
| partial_name | Liefert oder setzt den Teilnamen des Feldes. |
| alternate_name | Liefert oder setzt den alternativen Namen des Feldes (Ein alternatives Feld <br/>            Name, der anstelle des tatsächlichen Feldnamens verwendet werden soll <br/>            überall dort, wo das Feld in der Benutzeroberfläche identifiziert wird).<br/>            Der alternative Name wird als Feld‑Tooltip in Adobe Acrobat verwendet. |
| mapping_name | Liefert oder setzt den Mapping-Namen des Feldes, der beim Exportieren interaktiver Formularfelddaten aus dem Dokument verwendet werden soll. |
| Wert | Liefert oder setzt den Wert des Feldes. |
| is_synchronized | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| sync_root | Synchronisationsobjekt. |
| is_group | Ruft den booleschen Wert ab oder legt ihn fest, der anzeigt, ob dieses Feld ein Nicht‑Endfeld ist, d. h. eine Gruppe von Feldern. |
| annotation_index | Ruft den Index dieser Anmerkung auf der Seite ab oder legt ihn fest. |
| is_shared_field | Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld in Kopf‑ oder Fußzeile eingefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild ist auf allen Seiten des Dokuments sichtbar. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt. |
| fit_into_rectangle | Wenn true, wird die Schriftgröße reduziert, um den Text in das angegebene Rechteck einzupassen. |
| max_font_size | Maximale Schriftgröße, die für den Feldinhalt verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| min_font_size | Minimale Schriftgröße, die für den Feldinhalt verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| tab_order | Ruft die Tab‑Reihenfolge des Feldes ab oder legt sie fest. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Ruft das Unterfeld, das in diesem Feld über den Index enthalten ist, ab. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Keine |
| get_rectangle(consider_rotation) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitenrotation berücksichtigt wird. |
| accept(visitor) | Akzeptiert Besucher. |
| flatten() | Entfernt dieses Feld und legt seinen Wert direkt auf der Seite ab. |
| change_after_resize(transform) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |
| recalculate() | Berechnet alle berechneten Felder im Formular neu. |
| copy_to(array, index) | Kopiert Unterfelder dieses Feldes in das Array, beginnend ab dem angegebenen Index. |
| set_position(point) | Setzt die Position des Feldes. |

### Siehe auch

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

