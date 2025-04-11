---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineCollection-Klasse. Stellt die Hierarchie des Dokumenten-Outline dar
type: docs
weight: 8000
url: /de/net/aspose.pdf/outlinecollection/
---
## OutlineCollection-Klasse

Stellt die Hierarchie des Dokumenten-Outline dar.

```csharp
public sealed class OutlineCollection : Outlines
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Anzahl der Elemente in der Sammlung. Bitte nicht mit VisibleCount verwechseln: VisibleCount gibt die Anzahl der sichtbaren Outline-Elemente auf allen Ebenen zurück. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Gibt ein Outline-Element zurück, das das erste Element der obersten Ebene im Outline darstellt. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf diese Sammlung synchronisiert ist (thread-sicher). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Gibt ein Outline-Element aus der Sammlung nach Index zurück. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Gibt ein Outline-Element zurück, das das letzte Element der obersten Ebene im Outline darstellt. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Die Anzahl ist die Summe der Anzahl der sichtbaren abgeleiteten Outline-Elemente auf allen Ebenen. Hinweis: Bitte nicht mit Count verwechseln, das die Anzahl der Elemente in der Sammlung angibt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Fügt ein Outline-Element zur Sammlung hinzu. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Löscht alle Elemente aus der Sammlung. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Überprüft, ob die Sammlung das angegebene Element enthält. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Kopiert die Outline-Elemente in ein System.Array, beginnend an einem bestimmten System.Array-Index. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Löscht alle Outline-Elemente aus dem Dokumenten-Outline. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Löscht das Outline-Element mit dem angegebenen Titel aus dem Dokumenten-Outline. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Entfernt ein Element nach Index. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Wirft immer eine NotImplementedException |

### Siehe auch

* Klasse [Outlines](../outlines/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)