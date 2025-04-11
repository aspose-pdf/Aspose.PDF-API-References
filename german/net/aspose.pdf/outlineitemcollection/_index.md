---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineItemCollection-Klasse. Stellt einen Gliederungseintrag in der Gliederungshierarchie des PDF-Dokuments dar
type: docs
weight: 8010
url: /de/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection-Klasse

Stellt einen Gliederungseintrag in der Gliederungshierarchie des PDF-Dokuments dar.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Initialisiert die Gliederungselementinstanz mit dem Wurzelhierarchieobjekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Ruft die Aktion für dieses Gliederungselement ab oder legt sie fest. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Ruft das Fettdruckflag für den Titeltext dieses Gliederungselements ab oder legt es fest. |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Ruft die Farbe für den Titeltext dieses Gliederungselements ab oder legt sie fest. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Anzahl der Elemente in der Sammlung. Bitte nicht mit VisibleCount verwechseln: VisibleCount gibt die Anzahl der sichtbaren Gliederungselemente auf allen Ebenen zurück. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Ruft das Ziel für dieses Gliederungselement ab oder legt es fest. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Ruft das Gliederungselement ab, das das erste Element der obersten Ebene in der Gliederungshierarchie darstellt. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Überprüft, ob das Gliederungselement das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Ruft einen Wert ab, der angibt, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Ruft den Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert ist (thread-sicher). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Ruft das Kursivflag für den Titeltext dieses Gliederungselements ab oder legt es fest. |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Ruft das Gliederungselement aus der Sammlung anhand des Index ab. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Ruft das Gliederungselement ab, das das letzte Element der obersten Ebene in der Gliederungshierarchie darstellt. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Ruft die Hierarchieebene des Gliederungselements ab. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Ruft das Gliederungselement ab, das das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Ruft den offenen Status (true/false) für das Gliederungselement ab oder legt ihn fest. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Ruft das übergeordnete Objekt dieses Gliederungselements in der Gliederungshierarchie ab. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Ruft das Gliederungselement ab, das das vorherige Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Ruft das Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Ruft den Titel für dieses Gliederungselement ab oder legt ihn fest. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Ruft die Gesamtzahl der Gliederungselemente auf allen Ebenen in der Gliederungshierarchie des Dokuments ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Fügt der Sammlung ein Gliederungselement hinzu. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Löscht alle Elemente aus der Sammlung. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Überprüft, ob die Sammlung das angegebene Element enthält. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Kopiert die Gliederungseinträge in ein System.Array, beginnend an einem bestimmten System.Array-Index. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Löscht dieses Gliederungselement aus der Gliederungshierarchie des Dokuments. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Löscht den Gliederungseintrag mit dem angegebenen Namen aus der Gliederungshierarchie des Dokuments. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Fügt das Gliederungselement an der angegebenen Stelle in die Sammlung ein. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Entfernt das Element nach Index. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Entfernt das Gliederungssammlungselement. |

### Siehe auch

* Klasse [Outlines](../outlines/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)