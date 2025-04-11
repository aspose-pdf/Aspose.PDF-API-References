---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.DictionaryEditor-Klasse. Eine Klasse zum Zugriff auf das Baumwörterbuch eines Dokuments (Dokumentenwörterbuch, Seitenwörterbuch, Ressourcenwörterbuch).
type: docs
weight: 3470
url: /de/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Klasse DictionaryEditor

Eine Klasse zum Zugriff auf das Baumwörterbuch eines Dokuments (Dokumentenwörterbuch, Seitenwörterbuch, Ressourcenwörterbuch).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Vollständige Sammlung von Schlüsseln. Enthält bearbeitbare und nicht bearbeitbare Schlüssel. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Gibt die Anzahl der Elemente im `DictionaryEditor` zurück. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob der `DictionaryEditor` schreibgeschützt ist. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Ruft das Element mit dem angegebenen Schlüssel ab oder legt es fest. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Sammlung von bearbeitbaren Schlüsseln. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Gibt eine ICollection zurück, die die Werte im `DictionaryEditor` enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Setzt [`ICosPdfPrimitive`](../icospdfprimitive/) in das Wörterbuch. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Setzt [`ICosPdfPrimitive`](../icospdfprimitive/) in das Wörterbuch. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Entfernt alle Elemente aus dem `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Bestimmt, ob der `DictionaryEditor` einen bestimmten Wert enthält. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Bestimmt, ob der `DictionaryEditor` ein Element mit dem angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Entfernt das Element mit dem angegebenen Schlüssel aus dem `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Für den Zugriff auf einfache Datentypen wie string, name, bool, nummer. Gibt null für andere Typen zurück. |

### Siehe auch

* Schnittstelle [ICosPdfPrimitive](../icospdfprimitive/)
* Namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../)