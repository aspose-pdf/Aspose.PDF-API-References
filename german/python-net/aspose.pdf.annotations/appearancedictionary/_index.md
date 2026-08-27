---
title: "AppearanceDictionary"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Annotationsaussehens‑Dictionary, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll."
type: docs
weight: 60
url: /de/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Annotationsaussehens‑Dictionary, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll.

Der Typ AppearanceDictionary stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_fixed_size | Liest einen Wert, der angibt, ob das Wörterbuch eine feste Größe hat. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | D).state Werte,<br/>            wobei N - normale Darstellung, R - Rollover-Darstellung, D - gedrückte Darstellung und state - der Name des Zustands<br/>            (z. B. An, Aus für Kontrollkästchen). |
| Werte | Ruft die Liste der Wörterbuchwerte ab. <br/>            Die Ergebnis­sammlung enthält die Liste der XForm‑Objekte. |
| is_synchronized | Ruft einen Wert ab, der angibt, ob der Zugriff auf das Wörterbuch synchronisiert (thread‑sicher) ist. |
| sync_root | Ruft ein Objekt ab, das verwendet werden kann, um den Zugriff auf das Wörterbuch zu synchronisieren. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| add(key, value) | Fügt ein Element mit dem angegebenen Schlüssel und Wert hinzu. |
| add(key, value) | Fügt ein X‑Formular für den angegebenen Schlüssel hinzu. |
| copy_to(array, index) | Kopiert die Elemente des Wörterbuchs in ein Array, beginnend an einem bestimmten Array‑Index. |
| contains_key(key) | Bestimmt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| remove(key) | Entfernt den Schlüssel aus dem Wörterbuch. |
| try_get_value(key, value) | Versucht, den Schlüssel im Wörterbuch zu finden und gibt den Wert zurück, falls gefunden. |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

