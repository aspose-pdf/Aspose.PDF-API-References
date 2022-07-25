---
title: OutlineItemCollection
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt den Gliederungseintrag in der Gliederungshierarchie des PDF-Dokuments dar.
type: docs
weight: 5770
url: /de/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Stellt den Gliederungseintrag in der Gliederungshierarchie des PDF-Dokuments dar.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection)(OutlineCollection) | Initialisiert die Gliederungselementinstanz mithilfe des Stammhierarchieobjekts. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action) { get; set; } | Ruft die Aktion für dieses Gliederungselement ab oder legt sie fest. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold) { get; set; } | Holt oder setzt Fett-Flag für den Titeltext dieses Gliederungselements |
| [Color](../../aspose.pdf/outlineitemcollection/color) { get; set; } | Ruft die Farbe für den Titeltext dieses Gliederungselements ab oder legt sie fest. |
| override [Count](../../aspose.pdf/outlineitemcollection/count) { get; } | Anzahl der Sammlungselemente. Bitte nicht mit VisibleCount verwechseln: VisibleCount erhält die Anzahl der sichtbaren Gliederungselemente auf allen Ebenen. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination) { get; set; } | Ruft das Ziel für dieses Gliederungselement ab oder legt es fest. |
| [First](../../aspose.pdf/outlineitemcollection/first) { get; } | Ruft das Gliederungselement ab, das das erste Element der obersten Ebene in der Gliederungshierarchie darstellt. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext) { get; } | Überprüfen Sie, ob Gliederungselement das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly) { get; } | Ruft einen Wert ab, der angibt, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized) { get; } | Ruft den Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (threadsicher) ist. |
| [Italic](../../aspose.pdf/outlineitemcollection/italic) { get; set; } | Liest oder setzt Kursiv-Flag für den Titeltext dieses Gliederungselements |
| [Item](../../aspose.pdf/outlineitemcollection/item) { get; } | Ruft Gliederungselement aus der Sammlung mit Index ab. |
| [Last](../../aspose.pdf/outlineitemcollection/last) { get; } | Ruft das Gliederungselement ab, das das letzte Element der obersten Ebene in der Gliederungshierarchie darstellt. |
| [Level](../../aspose.pdf/outlineitemcollection/level) { get; } | Ruft die Hierarchieebene des Gliederungselements ab. |
| [Next](../../aspose.pdf/outlineitemcollection/next) { get; } | Ruft das Gliederungselement ab, das das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [Open](../../aspose.pdf/outlineitemcollection/open) { get; set; } | Abrufen oder Festlegen des offenen Status (wahr/falsch) für Gliederungselement. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent) { get; } | Ruft das übergeordnete Objekt dieses Gliederungselements in der Gliederungshierarchie ab. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev) { get; } | Ruft das Gliederungselement ab, das das vorherige Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot) { get; } | Ruft das Objekt ab, das zum Synchronisieren des Zugriffs auf diese Sammlung verwendet werden kann. |
| [Title](../../aspose.pdf/outlineitemcollection/title) { get; set; } | Ruft den Titel für dieses Gliederungselement ab oder legt ihn fest. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount) { get; } | Ruft die Gesamtzahl der Gliederungselemente auf allen Ebenen in der Gliederungshierarchie des Dokuments ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add)(OutlineItemCollection) | Gliederungselement zur Sammlung hinzufügen. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear)() | Löscht alle Elemente aus der Sammlung. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains)(OutlineItemCollection) | Überprüft, ob die Sammlung das angegebene Element enthält. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto)(OutlineItemCollection[], int) | Kopiert die Gliederungseinträge in ein System.Array, beginnend bei einem bestimmten System.Array-Index. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete)() | Löscht dieses Gliederungselement aus der Gliederungshierarchie des Dokuments. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete_1)(string) | Löscht den Gliederungseintrag mit dem angegebenen Namen aus der Gliederungshierarchie des Dokuments. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert)(int, OutlineItemCollection) | Fügt das Gliederungselement an der angegebenen Stelle in die Sammlung ein. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove#remove_1)(int) | Element nach Index entfernen. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove#remove)(OutlineItemCollection) | Element der Gliederungssammlung entfernen. |

### Siehe auch

* class [Outlines](../outlines)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
