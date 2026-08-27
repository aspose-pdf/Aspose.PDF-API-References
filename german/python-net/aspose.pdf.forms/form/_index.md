---
title: "Form"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die ein Formularobjekt darstellt."
type: docs
weight: 110
url: /de/python-net/aspose.pdf.forms/form/
---

## Form class

Klasse, die ein Formularobjekt darstellt.

Der Form‑Typ stellt die folgenden Member bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_synchronized | Gibt true zurück, wenn das Objekt thread‑sicher ist. |
| sync_root | Gibt das Synchronisationsobjekt zurück. |
| auto_recalculate | Wenn gesetzt, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist true. Auf false setzen, um die Leistung zu steigern, wenn das Formular mit einer großen Anzahl berechneter Felder ausgefüllt wird. |
| auto_restore_form | Wenn gesetzt, werden fehlende Formularfelder automatisch erstellt, sofern sie in Anmerkungen vorhanden sind. |
| default_resources | Liest die Standardressourcen, die in diesem Formular platziert sind. |
| default_appearance | Liest oder setzt das Standardaussehen des Formulars (Objekt, das Standardschriftart, Textgröße und Farbe für Felder im Formular beschreibt). |
| xfa | Liest XFA-Daten des Formulars (falls vorhanden). |
| ignore_needs_rendering | Wenn diese Eigenschaft true ist, wird der Wert des Schlüssels NeedsRendering während der Konvertierung <br/>            XFA-Formular in ein Standardformular ignoriert. Standardmäßig ist sie false. |
| remove_permission | Wenn diese Eigenschaft true ist, wird das "Perms"-Dictionary nach der Konvertierung <br/>            dynamischer Dokumente in ein Standarddokument aus dem PDF-Dokument entfernt. Das "Perms"-Dictionary kann Regeln enthalten, die die Anzeigeauswahl von <br/>            Pflichtfeldern im Adobe Acrobat Reader stören.<br/>            Standardmäßig ist es false. |
| emulate_requierd_groups | Wenn diese Eigenschaft true ist, werden zusätzliche rote Begrenzungsrechtecke für erforderliche XFA‑exclGroup‑Elementcontainer gezeichnet<br/>            Diese Eigenschaft wurde eingeführt, weil während der Konvertierung der XFA‑Darstellung von Formularen <br/>            in ein Standardformat Analoga für exclGroup fehlen.<br/>            Standardmäßig ist sie false. |
| type | Liest den Typ des Formulars. Mögliche Werte sind: Standard, Statisch, Dynamisch. |
| fields | Liest die Liste aller Felder auf der niedrigsten Ebene des hierarchischen Formulars. |
| signatures_exist | Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld. |
| signatures_append_only | Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei (geschrieben) auf eine Weise gespeichert wird, die ihren vorherigen Inhalt ändert, <br/>            im Gegensatz zu einem inkrementellen Update. |
| sign_dependent_elements_rendering_mode_when_converted | Formulare können Signaturinformationen enthalten, d.h. sie können signiert oder unsigniert sein.<br/>              Und die Ansicht des Formulars muss manchmal davon abhängen, ob das Formular signiert ist oder nicht.<br/>              Diese Eigenschaft teilt dem Formularkonverter mit (z.B. bei der Konvertierung eines XFA‑Formulars in ein Standardformular),<br/>              ob das Ergebnisformular als signiert oder als unsigniert gerendert werden soll. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Liest das Feld des Formulars anhand des Feldindex. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| delete(field) | Löscht das Feld aus dem Formular. |
| delete(field_name) | Löscht das Feld aus dem Formular anhand seines Namens. |
| add(field, page_number) | Fügt ein Feld zum Formular hinzu. |
| add(field) | Fügt ein Feld zum Formular hinzu. |
| add(field, partial_name, page_number) | Fügt ein neues Feld zum Formular hinzu; Wenn dieses Feld bereits auf einem anderen oder diesem Formular platziert ist, wird eine Kopie des Feldes erstellt. |
| has_field(field) | Überprüfen, ob das Formular das angegebene Feld bereits enthält. |
| has_field(field_name) | Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde. |
| copy_to(array, index) | Kopiert Felder, die im Formular platziert wurden, in ein Array. |
| flatten() | Entfernt alle Formularfelder und legt deren Werte direkt auf der Seite ab. |
| add_field_appearance(field, page_number, rect) | Fügt ein zusätzliches Erscheinungsbild des Feldes zur angegebenen Seite des Dokuments an der angegebenen Position hinzu. |
| get_fields_in_rect(rect) | Gibt Felder innerhalb des angegebenen Rechtecks zurück. |

### Siehe auch

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

