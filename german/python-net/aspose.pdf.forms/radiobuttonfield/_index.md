---
title: "RadioButtonField"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die ein Optionsfeld (Radio‑Button) darstellt."
type: docs
weight: 220
url: /de/python-net/aspose.pdf.forms/radiobuttonfield/
---

## RadioButtonField class

Klasse, die ein Optionsfeld (Radio‑Button) darstellt.

Der Typ RadioButtonField stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| RadioButtonField(page) | Initialisiert eine neue Instanz der Klasse RadioButtonField |
| RadioButtonField(doc) | Initialisiert eine neue Instanz der Klasse RadioButtonField |
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
| anmerkung_typ | Keine |
| breite | Keine |
| aktionen | Keine |
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
| seiten_index | Liest den Index der Seite, die dieses RadioButton‑Feld enthält. |
| bei_aktivierung | Keine |
| Hervorhebung | Keine |
| Eltern | Keine |
| default_appearance | Keine |
| read_only | Keine |
| required | Keine |
| exportable | Keine |
| partial_name | Liefert oder setzt den Teilnamen des Feldes. |
| alternate_name | Liefert oder setzt den alternativen Namen des Feldes (Ein alternatives Feld <br/>            Name, der anstelle des tatsächlichen Feldnamens verwendet werden soll <br/>            überall dort, wo das Feld in der Benutzeroberfläche identifiziert wird).<br/>            Der alternative Name wird als Feld‑Tooltip in Adobe Acrobat verwendet. |
| mapping_name | Liefert oder setzt den Mapping-Namen des Feldes, der beim Exportieren interaktiver Formularfelddaten aus dem Dokument verwendet werden soll. |
| Wert | Liest oder setzt den Wert des Feldes. |
| is_synchronized | Gibt true zurück, wenn das Wörterbuch synchronisiert ist. |
| sync_root | Synchronisationsobjekt. |
| is_group | Ruft den booleschen Wert ab oder legt ihn fest, der anzeigt, ob dieses Feld ein Nicht‑Endfeld ist, d. h. eine Gruppe von Feldern. |
| annotation_index | Ruft den Index dieser Anmerkung auf der Seite ab oder legt ihn fest. |
| is_shared_field | Eigenschaft zur Unterstützung des Generators. Wird verwendet, wenn das Feld in Kopf‑ oder Fußzeile eingefügt wird. Wenn true, wird dieses Feld einmal erstellt und sein Erscheinungsbild ist auf allen Seiten des Dokuments sichtbar. Wenn false, wird für jede Dokumentseite ein separates Feld erstellt. |
| fit_into_rectangle | Wenn true, wird die Schriftgröße reduziert, um den Text in das angegebene Rechteck einzupassen. |
| max_font_size | Maximale Schriftgröße, die für den Feldinhalt verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| min_font_size | Minimale Schriftgröße, die für den Feldinhalt verwendet werden kann. -1, um die Größe nicht zu prüfen. |
| tab_order | Ruft die Tab‑Reihenfolge des Feldes ab oder legt sie fest. |
| commit_immediately | Liest oder setzt das Flag für das sofortige Commit bei Auswahländerung. |
| multi_select | Liest oder setzt das Mehrfachauswahl-Flag. |
| ausgewählt | Liest oder setzt den Index des ausgewählten Elements. Die Nummerierung der Elemente beginnt bei 1. |
| selected_items | Liest oder setzt das Array der ausgewählten Elemente. Für eine Mehrfachauswahl‑Liste enthält das Array mehr als ein Element. Für eine Einzel­auswahl‑Liste enthält es ein einzelnes Element. |
| Optionen | Liest die Sammlung der Optionen des Radio‑Buttons. |
| style | Stil des Feldkastens. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Ruft das Unterfeld, das in diesem Feld über den Index enthalten ist, ab. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| add_option(option_name, rect) | Füge zur Radio-Button-Option mit angegebenem Rechteck hinzu. |
| add_option(option_name) | Füge zur Radio-Button-Option mit angegebenem Rechteck hinzu. |
| add_option(export, name) | Füge zur Radio-Button-Option mit angegebenem Rechteck hinzu. |
| clone() | Keine |
| get_rectangle(consider_rotation) | Keine |
| accept(visitor) | Keine |
| flatten() | Entfernt dieses Feld und legt seinen Wert direkt auf der Seite ab. |
| change_after_resize(transform) | Keine |
| recalculate() | Berechnet alle berechneten Felder im Formular neu. |
| copy_to(array, index) | Kopiert Unterfelder dieses Feldes in das Array, beginnend ab dem angegebenen Index. |
| set_position(point) | Verschiebe alle Unterelemente des Radio-Buttons zu den angegebenen Positionen auf der Seite. |
| delete_option(option_name) | Löscht die Option anhand ihres Namens. |
| add(new_item) | Fügt ein neues Optionsfeld zum RadioButton-Feld hinzu. |

### Siehe auch

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

