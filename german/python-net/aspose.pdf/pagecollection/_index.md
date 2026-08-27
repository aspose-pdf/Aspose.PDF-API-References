---
title: "PageCollection"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Sammlung von PDF-Dokumentseiten."
type: docs
weight: 1100
url: /de/python-net/aspose.pdf/pagecollection/
---

## PageCollection class

Sammlung von PDF-Dokumentseiten.

Der PageCollection-Typ stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_synchronized | Gibt true zurück, wenn das Objekt synchronisiert ist. |
| sync_root | Liefert das Synchronisationsobjekt der Sammlung. |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Liefert die Seite nach Index. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| add(entity) | Fügt eine Seite zur Sammlung hinzu. |
| add() | Fügt eine Seite zur Sammlung hinzu. |
| add(pages) | Fügt der Sammlung alle Seiten aus der Liste hinzu. |
| add(pages) | Fügt der Sammlung alle Seiten aus dem Array hinzu. |
| delete(index) | Löscht die angegebene Seite. |
| delete() | Löscht die angegebene Seite. |
| delete(pages) | Löscht die angegebenen Seiten, deren Nummern im Array angegeben sind. |
| accept(visitor) | Akzeptiert das [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) Besucherobjekt, das Funktionalität zum Arbeiten mit Anmerkungen bereitstellt. |
| accept(visitor) | Akzeptiert das [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) Besucherobjekt, das Funktionalität zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| accept(visitor) | Akzeptiert das [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| accept(visitor) | Akzeptiert das [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| insert(page_number) | Fügt eine leere Seite in die Sammlung an der angegebenen Position ein. |
| insert(page_number, entity) | Fügt eine leere Seite in die Sammlung an der angegebenen Position ein. |
| insert(page_number, pages) | Fügt Seiten aus der Sammlung in das Dokument ein. |
| insert(page_number, pages) | Fügt Seiten aus dem Array in das Dokument ein. |
| index_of(entity) | Gibt den Index der angegebenen Seite zurück. |
| flatten() | Entfernt alle Felder, die sich auf den Seiten befinden, und ersetzt sie durch deren Werte. |
| free_memory() | Löscht zwischengespeicherte Daten |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

