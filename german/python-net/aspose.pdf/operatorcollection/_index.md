---
title: "OperatorCollection"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse stellt eine Sammlung von Operatoren dar"
type: docs
weight: 1010
url: /de/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

Klasse stellt eine Sammlung von Operatoren dar

Der Typ OperatorCollection stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_fast_text_extraction_mode | Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Liefert den Operator anhand seines Index. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| insert(index, op) | Fügt einen Operator in die Sammlung ein. |
| insert(at, ops) | Fügt Operatoren an der angegebenen Position ein. |
| insert(at, ops) | Fügt einen Operator in die Sammlung ein. |
| delete(index) | Löscht einen Operator aus der Sammlung. |
| delete(ops) | Löscht Operatoren aus der Sammlung. |
| delete(list) | Keine |
| add(ops) | Fügt Operatoren am Ende der Inhaltsoperatoren hinzu. |
| add(ops) | Fügt einen neuen Operator in die Sammlung ein. |
| suppress_update() | Unterdrückt die Aktualisierung von Inhaltsdaten.<br/>            Der Inhaltsstrom wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| resume_update() | Setzt die Dokumentenaktualisierung fort.<br/>            Aktualisiert den Inhaltsstrom, falls ausstehende Änderungen vorhanden sind. |
| cancel_update() | Bricht die letzte Aktualisierung ab.<br/>            Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll. |
| accept(visitor) | Akzeptiert ein IOperatorSelector-Besucherobjekt, um Operatoren zu verarbeiten. |
| replace(operators) | Ersetzen Sie Operatoren in der Sammlung durch andere Operatoren. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

