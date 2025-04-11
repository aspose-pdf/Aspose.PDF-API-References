---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor-Methode. Entfernt das Element mit dem angegebenen Schlüssel aus dem DictionaryEditor
type: docs
weight: 140
url: /de/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Entfernt das Element mit dem angegebenen Schlüssel aus dem [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Der Schlüssel des zu entfernenden Elements. |

### Rückgabewert

True, wenn das Element erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt auch false zurück, wenn der Schlüssel im ursprünglichen Wörterbuch nicht gefunden wurde oder der Schlüssel nicht bearbeitbar ist.

### Siehe auch

* Klasse [DictionaryEditor](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | KeyValuePair`2 | Das Objekt, das aus dem [`DictionaryEditor`](../) entfernt werden soll. |

### Rückgabewert

true, wenn das Element erfolgreich aus dem [`DictionaryEditor`](../) entfernt wurde; andernfalls false. Diese Methode gibt auch false zurück, wenn das Element im ursprünglichen [`DictionaryEditor`](../) nicht gefunden wird.

### Siehe auch

* Schnittstelle [ICosPdfPrimitive](../../icospdfprimitive/)
* Klasse [DictionaryEditor](../)
* Namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* Assembly [Aspose.PDF](../../../)