---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary-Methode. Für den Zugriff auf einfache Datentypen wie String, Name, Bool, Zahl. Gibt null für andere Typen zurück
type: docs
weight: 170
url: /de/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue-Methode

Für den Zugriff auf einfache Datentypen wie String, Name, Bool, Zahl. Gibt null für andere Typen zurück.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Schlüsselwert |
| value | ICosPdfPrimitive& | gibt [`ICosPdfPrimitive`](../../icospdfprimitive/) für den Schlüssel oder null zurück. |

### Rückgabewert

Gibt true zurück, wenn [`ICosPdfPrimitive`](../../icospdfprimitive/) wie String, Name, Bool, Zahl ist. Gibt false für alle anderen Typen zurück.

### Siehe auch

* Schnittstelle [ICosPdfPrimitive](../../icospdfprimitive/)
* Klasse [CosPdfDictionary](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)