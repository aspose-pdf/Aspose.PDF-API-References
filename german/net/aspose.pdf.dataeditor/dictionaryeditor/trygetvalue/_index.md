---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor-Methode. Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück
type: docs
weight: 150
url: /de/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue-Methode

Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Schlüsselwert |
| value | ICosPdfPrimitive& | gibt [`ICosPdfPrimitive`](../../icospdfprimitive/) für den Schlüssel oder null zurück. |

### Rückgabewert

Gibt true zurück, wenn [`ICosPdfPrimitive`](../../icospdfprimitive/) wie string, name, bool, number ist. Gibt false für alle anderen Typen zurück.

### Siehe auch

* Schnittstelle [ICosPdfPrimitive](../../icospdfprimitive/)
* Klasse [DictionaryEditor](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)