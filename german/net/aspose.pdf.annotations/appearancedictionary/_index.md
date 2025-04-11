---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary-Klasse. Annotation Erscheinungsdictionary, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll
type: docs
weight: 1490
url: /de/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary-Klasse

Annotation Erscheinungsdictionary, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Gibt die Anzahl der im Dictionary enthaltenen Elemente zurück. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Gibt einen Wert zurück, der angibt, ob das Dictionary eine feste Größe hat. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob das Dictionary schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf das Dictionary synchronisiert ist (thread-sicher). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Stellt eine bequeme Form zum Abrufen von Erscheinungsstreams dar. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Gibt die Schlüssel des Dictionaries zurück. Wenn das Erscheinungsdictionary Unterdictionaries hat, dann enthält [`Keys`](./keys/) (N&#x7C;R&#x7C;D).state-Werte, wobei N - normale Erscheinung, R - Hover-Erscheinung, D - gedrückte Erscheinung und state - der Name des Zustands (z.B. Ein, Aus für Kontrollkästchen). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf das Dictionary zu synchronisieren. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Gibt die Liste der Werte des Dictionaries zurück. Die Ergebnis-Kollektion enthält die Liste der XForm-Objekte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Fügt ein Paar mit Schlüssel und Wert in das Dictionary ein. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Fügt eine X-Form für den angegebenen Schlüssel hinzu. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Entfernt alle Elemente aus dem Dictionary. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Überprüft, ob das angegebene Schlüssel-Wert-Paar im Dictionary enthalten ist. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Bestimmt, ob dieses Dictionary den angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Kopiert die Elemente des Dictionaries in ein Array, beginnend an einem bestimmten Array-Index. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Gibt ein IDictionaryEnumerator-Objekt für das Dictionary zurück. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Entfernt das Schlüssel/Wert-Paar aus der Sammlung. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Entfernt den Schlüssel aus dem Dictionary. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Versucht, den Schlüssel im Dictionary zu finden und den Wert abzurufen, wenn er gefunden wird. |

### Siehe auch

* Klasse [XForm](../../aspose.pdf/xform/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)