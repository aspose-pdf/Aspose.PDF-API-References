---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary-Eigenschaft. Ruft das Element mit dem angegebenen Schlüssel ab oder setzt es
type: docs
weight: 60
url: /de/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary-Indexer

Ruft das Element mit dem angegebenen Schlüssel ab oder setzt es.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| key | Der Schlüssel des Elements, das abgerufen oder gesetzt werden soll. |

### Rückgabewert

Das Element mit dem angegebenen Schlüssel.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Der Schlüssel ist null. |
| KeyNotFoundException | Die Eigenschaft wird abgerufen und der Schlüssel wird nicht gefunden. |
| ArgumentException | Wirft eine Ausnahme, wenn der Schlüssel nicht bearbeitet/gesetzt werden kann. |

### Siehe auch

* Schnittstelle [ICosPdfPrimitive](../../icospdfprimitive/)
* Klasse [CosPdfDictionary](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)