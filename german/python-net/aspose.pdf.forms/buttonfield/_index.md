---
title: "ButtonField"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse stellt ein Push‑Button‑Feld dar."
type: docs
weight: 20
url: /de/python-net/aspose.pdf.forms/buttonfield/
---

## ButtonField class

Klasse stellt ein Push‑Button‑Feld dar.

Der Typ ButtonField stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| ButtonField() | Button-Feld-Konstruktor für Generator. |
| ButtonField(page, rect) | Initialisiert eine neue Instanz der Klasse ButtonField |
| ButtonField(doc, rect) | Initialisiert eine neue Instanz der Klasse ButtonField |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Keine |
| horizontal_alignment | Keine |
| Rand | Keine |
| is_first_paragraph_in_column | Keine |
| is_kept_with_next | Keine |
| is_in_new_page | Keine |
| is_in_line_paragraph | Keine |
| Hyperlink | Keine |
| z_index | Keine |
| aktualisiere_erscheinung_beim_konvertieren | Keine |
| verwende_schriftart_teilmenge | Keine |
| flaggen | Keine |
| anmerkung_typ | Ermittelt den Typ der Anmerkung. |
| breite | Keine |
| aktionen | Ermittelt die Anmerkungsaktionen. |
| höhe | Keine |
| rechteck | Ermittelt oder setzt das Feldrechteck. |
| inhalt | Keine |
| Name | Keine |
| geändert | Keine |
| farbe | Keine |
| rahmen | Keine |
| aktiver_zustand | Keine |
| eigenschaften | Keine |
| zustände | Keine |
| ausrichtung | Keine |
| text_horizontale_ausrichtung | Keine |
| vollständiger_name | Keine |
| erscheinung | Keine |
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
| normal_caption | Liest oder legt die normale Beschriftung fest. |
| rollover_caption | Liest oder setzt die Roll‑over‑Beschriftung der Schaltfläche, die angezeigt wird, wenn der Benutzer den Zeiger <br/>            in den aktiven Bereich bewegt, ohne die Maustaste zu drücken. |
| alternate_caption | Liest oder setzt die alternative Beschriftung der Schaltfläche, die angezeigt wird <br/>            wenn die Maustaste innerhalb des aktiven Bereichs gedrückt wird. |
| normal_icon | Liest oder setzt das normale Symbol der Schaltfläche, das angezeigt wird, wenn keine Interaktion mit dem Benutzer stattfindet. |
| rollover_icon | Liest oder setzt das Roll‑over‑Symbol der Schaltfläche, das angezeigt wird, wenn der Benutzer <br/>            den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken. |
| alternate_icon | Liest oder setzt das alternative Symbol, das angezeigt wird, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt wird. |
| icon_fit | Liest das Icon‑Fit‑Objekt, das angibt, wie das Symbol der Widget‑Annotation innerhalb ihres Annotationsrechtecks angezeigt wird. |
| ic_position | Liest oder setzt die Position der Symbolbeschriftung. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Ruft das Unterfeld, das in diesem Feld über den Index enthalten ist, ab. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Keine |
| get_rectangle(consider_rotation) | Keine |
| accept(visitor) | Akzeptiert Besucher. |
| flatten() | Entfernt dieses Feld und legt seinen Wert direkt auf der Seite ab. |
| change_after_resize(transform) | Keine |
| recalculate() | Berechnet alle berechneten Felder im Formular neu. |
| copy_to(array, index) | Kopiert Unterfelder dieses Feldes in das Array, beginnend ab dem angegebenen Index. |
| set_position(point) | Setzt die Position des Feldes. |
| add_image(image) | Fügt ein Bild zu den Feldressourcen hinzu und zeichnet es. |

### Siehe auch

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

