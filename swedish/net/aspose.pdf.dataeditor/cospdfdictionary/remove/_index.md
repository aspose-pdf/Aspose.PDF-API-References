---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary-metod. Tar bort elementet med den angivna nyckeln från CosPdfDictionary
type: docs
weight: 150
url: /sv/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

Tar bort elementet med den angivna nyckeln från [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | Sträng | Nyckeln till elementet som ska tas bort. |

### Returvärde

Sant om elementet har tagits bort framgångsrikt; annars falskt. Denna metod returnerar också falskt om nyckeln inte hittades i den ursprungliga ordboken eller om nyckeln inte är redigerbar.

### Se Även

* klass [CosPdfDictionary](../)
* namnrymd [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* samling [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Tar bort den första förekomsten av ett specifikt objekt från [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Objektet som ska tas bort från [`CosPdfDictionary`](../). |

### Returvärde

Sant om item har tagits bort framgångsrikt från [`CosPdfDictionary`](../); annars falskt. Denna metod returnerar också falskt om item inte hittas i den ursprungliga [`CosPdfDictionary`](../).

### Se Även

* gränssnitt [ICosPdfPrimitive](../../icospdfprimitive/)
* klass [CosPdfDictionary](../)
* namnrymd [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* samling [Aspose.PDF](../../../)