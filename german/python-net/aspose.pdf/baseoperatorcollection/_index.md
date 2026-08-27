---
title: "BaseOperatorCollection"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt die Basisklasse für die Operator‑Sammlung dar."
type: docs
weight: 70
url: /de/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Stellt die Basisklasse für die Operator‑Sammlung dar.

Der BaseOperatorCollection-Typ stellt die folgenden Member bereit:
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
| suppress_update() | Unterdrückt die Aktualisierung von Inhaltsdaten.<br/>            Der Inhaltsstrom wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| resume_update() | Setzt die Dokumentenaktualisierung fort.<br/>            Aktualisiert den Inhaltsstrom, falls ausstehende Änderungen vorhanden sind. |
| insert(index, op) | Fügt einen Operator in die Sammlung ein. |
| cancel_update() | Bricht die letzte Aktualisierung ab.<br/>            Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

