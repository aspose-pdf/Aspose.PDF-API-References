---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.CosPdfDictionary-Klasse. Eine Klasse zum Zugreifen auf das Wörterbuch eines Objekts
type: docs
weight: 3420
url: /de/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary-Klasse

Eine Klasse zum Zugreifen auf das Wörterbuch eines Objekts.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Erstellt ein Wörterbuch aus Ressourcen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Vollständige Sammlung von Schlüsseln. Enthält bearbeitbare und nicht bearbeitbare Schlüssel. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Gibt die Anzahl der Elemente im `CosPdfDictionary` zurück. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob das `CosPdfDictionary` schreibgeschützt ist. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Ruft das Element mit dem angegebenen Schlüssel ab oder legt es fest. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Sammlung von bearbeitbaren Schlüsseln. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Ruft eine ICollection ab, die die Werte im `CosPdfDictionary` enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Erstellt ein leeres Wörterbuch, das dem Dokument angehängt wird. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Erstellt ein leeres Wörterbuch, das der Seite angehängt wird. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Setzt [`ICosPdfPrimitive`](../icospdfprimitive/) in das Wörterbuch. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Setzt [`ICosPdfPrimitive`](../icospdfprimitive/) in das Wörterbuch. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Entfernt alle Elemente aus dem `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Bestimmt, ob das `CosPdfDictionary` einen bestimmten Wert enthält. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Bestimmt, ob das `CosPdfDictionary` ein Element mit dem angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Entfernt das Element mit dem angegebenen Schlüssel aus dem `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Versucht, diese Instanz in [`CosPdfBoolean`](../cospdfboolean/) zu konvertieren. |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Versucht, diese Instanz in `CosPdfDictionary` zu konvertieren. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Versucht, diese Instanz in [`CosPdfName`](../cospdfname/) zu konvertieren. |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Versucht, diese Instanz in [`CosPdfNumber`](../cospdfnumber/) zu konvertieren. |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Versucht, diese Instanz in [`CosPdfString`](../cospdfstring/) zu konvertieren. |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück. |

### Siehe auch

* Klasse [CosPdfPrimitive](../cospdfprimitive/)
* Schnittstelle [ICosPdfPrimitive](../icospdfprimitive/)
* Namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../)