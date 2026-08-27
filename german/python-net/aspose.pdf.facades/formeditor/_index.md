---
title: "FormEditor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)"
type: docs
weight: 110
url: /de/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.)

Der FormEditor-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Initialisiert eine neue Instanz der Klasse FormEditor |
| FormEditor(src_file_name, dest_file_name) | Initialisiert eine neue Instanz der Klasse FormEditor |
| FormEditor() | Konstruktor für FormEditor. |
| FormEditor(document) | Initialisiert eine neue Instanz der Klasse FormEditor |
| FormEditor(document, dest_file_name) | Initialisiert eine neue Instanz der Klasse FormEditor |
| FormEditor(document, dest_stream) | Initialisiert eine neue Instanz der Klasse FormEditor |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| src_file_name | Liest oder setzt den Namen der Quelldatei. |
| dest_file_name | Liest oder setzt den Namen der Zieldatei. |
| src_stream | Liest oder setzt den Quell-Stream. |
| dest_stream | Liest oder setzt den Ziel-Stream. |
| Elemente | Setzt Elemente, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden. |
| export_items | Setzt Optionen für die Kombobox mit Exportwerten. |
| Fassade | Setzt visuelle Attribute des Feldes. |
| radio_gap | Das Mitglied, das den Abstand zwischen zwei benachbarten Optionsschaltern in Pixeln speichert, standardmäßig 50. |
| radio_horiz | Das Flag, das angibt, ob die Optionsschalter horizontal oder vertikal angeordnet sind, Standardwert ist wahr. |
| radio_button_item_size | Liest oder setzt die Größe des Optionsschalter-Elements (wenn ein neues Optionsschalter-Feld hinzugefügt wird). |
| submit_flag | Setzt die Übermittlungs-Flags des Absende-Buttons. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save() | Speichert Änderungen in die Zieldatei. |
| save(dest_file) | Speichert Änderungen in die Zieldatei. |
| save(dest_stream) | Speichert Änderungen in die Zieldatei. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Fügt ein Feld des angegebenen Typs zum Formular hinzu. |
| copy_inner_field(field_name, new_field_name, page_num) | Kopiert ein vorhandenes Feld an dieselbe Position in der angegebenen Seitennummer.<br/>            Ein neues Dokument wird erzeugt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Kopiert ein vorhandenes Feld an eine neue Position, die sowohl durch die Seitennummer als auch durch die Koordinaten angegeben ist.<br/>            Ein neues Dokument wird erzeugt, das alles enthält, was das Quelldokument hat, außer dem neu kopierten Feld. |
| copy_outer_field(src_file_name, field_name) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit ursprünglicher Seitennummer und Koordinaten.<br/>            Hinweis: Nur für AcroForm-Felder (ausgenommen Optionsfelder). |
| copy_outer_field(src_file_name, field_name, page_num) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und ursprünglichen Koordinaten.<br/>             Hinweis: Nur für AcroForm-Felder (ausgenommen Optionsfelder). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Kopiert ein vorhandenes Feld von einem PDF-Dokument in ein anderes Dokument mit angegebener Seitennummer und Koordinaten.<br/>            Hinweis: Nur für AcroForm-Felder (ausgenommen Optionsfelder). |
| decorate_field(field_name) | Ändert die visuellen Attribute des angegebenen Feldes. |
| decorate_field(field_type) | Ändert die visuellen Attribute aller Felder des angegebenen Feldtyps. |
| decorate_field() | Ändert die visuellen Attribute des angegebenen Feldes. |
| add_list_item(field_name, item_name) | Fügt ein neues Element zur Listbox hinzu. |
| add_list_item(field_name, export_name) | Fügt ein neues Element mit Exportwert zum bestehenden Listbox-Feld hinzu, nur für AcroForm-Combo-Box-Feld. |
| close() | Schließt die Fassade. |
| set_field_attribute(field_name, flag) | Setzt Attribute des Feldes. |
| set_field_appearance(field_name, flags) | Setzt Feld-Flags |
| get_field_appearance(field_name) | Liest Feld-Flags. |
| set_submit_flag(field_name, submit_form_flag) | Setzt das Submit-Flag des Submit-Buttons. |
| set_submit_url(field_name, url) | Setzt die URL des Buttons. |
| set_field_limit(field_name, field_limit) | Setzt die maximale Zeichenanzahl des Textfeldes. |
| set_field_comb_number(field_name, comb_number) | Setzt die Anzahl der Kästchen für ein reguläres einzeiliges Textfeld (das Feld wird <br/>            automatisch in so viele gleichmäßig verteilte Positionen, oder Kästchen, <br/>            aufgeteilt, wie der Wert des Parameters combNumber ist). |
| move_field(field_name, llx, lly, urx, ury) | Setzt die neue Position des Feldes. |
| remove_field(field_name) | Entfernt das Feld aus dem Formular. |
| reset_facade() | Setzt alle visuellen Attribute auf einen leeren Wert zurück. |
| reset_inner_facade() | Setzt alle visuellen Attribute der inneren Fassade auf einen leeren Wert zurück. |
| rename_field(field_name, new_field_name) | Ändert den Namen des Feldes. |
| remove_field_action(field_name) | Entfernt die Submit-Aktion des Feldes. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Fügt einen Submit-Button zum Formular hinzu. |
| del_list_item(field_name, item_name) | Löscht ein Element aus dem Listenfeld. |
| set_field_script(field_name, script) | Setzt JavaScript für ein PushButton-Feld. Wenn altes JavaScript existierte, wird es durch das neue ersetzt. |
| add_field_script(field_name, script) | Fügt JavaScript für ein PushButton-Feld hinzu. Wenn ein altes Ereignis existiert, wird das neue Ereignis dahinter eingefügt. |
| single_2_multiple(field_name) | Ändert ein einzeiliges Textfeld in ein mehrzeiliges. |
| set_field_alignment(field_name, alignment) | Setzt den Ausrichtungsstil eines Textfeldes. |
| set_field_alignment_v(field_name, alignment) | Setzt den vertikalen Ausrichtungsstil eines Textfeldes. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

