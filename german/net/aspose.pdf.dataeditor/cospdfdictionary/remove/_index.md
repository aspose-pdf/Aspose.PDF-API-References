---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary-Methode. Entfernt das Element mit dem angegebenen Schlüssel aus dem CosPdfDictionary
type: docs
weight: 150
url: /de/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

Entfernt das Element mit dem angegebenen Schlüssel aus dem [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Der Schlüssel des zu entfernenden Elements. |

### Rückgabewert

True, wenn das Element erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt auch false zurück, wenn der Schlüssel im ursprünglichen Wörterbuch nicht gefunden wurde oder der Schlüssel nicht bearbeitbar ist.

### Siehe auch

* Klasse [CosPdfDictionary](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | KeyValuePair`2 | Das Objekt, das aus dem [`CosPdfDictionary`](../) entfernt werden soll. |

### Rückgabewert

true, wenn das Element erfolgreich aus dem [`CosPdfDictionary`](../) entfernt wurde; andernfalls false. Diese Methode gibt auch false zurück, wenn das Element im ursprünglichen [`CosPdfDictionary`](../) nicht gefunden wird.

### Siehe auch

* Schnittstelle [ICosPdfPrimitive](../../icospdfprimitive/)
* Klasse [CosPdfDictionary](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)