---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DestinationCollection-Klasse. Die Klasse repräsentiert die Sammlung aller Ziele (eine Namensbaumzuordnung von Namenszeichenfolgen zu Zielen, siehe 12.3.2.3 "Benannte Ziele" und siehe 7.7.4 "Namenswörterbuch") im PDF-Dokument.
type: docs
weight: 3510
url: /de/net/aspose.pdf/destinationcollection/
---
## Klasse DestinationCollection

Die Klasse repräsentiert die Sammlung aller Ziele (eine Namensbaumzuordnung von Namenszeichenfolgen zu Zielen (siehe 12.3.2.3, "Benannte Ziele") und (siehe 7.7.4, "Namenswörterbuch")) im PDF-Dokument.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Gibt das Zielobjekt nach Index zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Fügt das angegebene Element hinzu. Die Sammlung ist schreibgeschützt. Wirft immer eine NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Die Sammlung ist schreibgeschützt. Wirft immer eine NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Bestimmt, ob diese Instanz das Objekt enthält. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Gibt den Enumerator zurück. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Gibt das explizite Ziel nach dem Namen zurück. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Gibt die Seitennummer des Ziels nach dem Namen zurück. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Gibt den Index des Ziels in der Sammlung zurück. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Entfernt das angegebene Element. Die Sammlung ist schreibgeschützt. Wirft immer eine NotSupportedException. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)