---
title: "CosPdfDictionary.Remove"
second_title: "Aspose.PDF för .NET API‑referens"
description: "CosPdfDictionary metod. Tar bort elementet med den angivna nyckeln från CosPdfDictionary"
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
| nyckel | String | Nyckeln för elementet som ska tas bort. |

### Returvärde

True om elementet har tagits bort framgångsrikt; annars false. Denna metod returnerar också false om nyckeln inte hittades i den ursprungliga ordboken eller nyckeln inte är redigerbar

### Se även

* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Tar bort den första förekomsten av ett specifikt objekt från [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Objektet att ta bort från [`CosPdfDictionary`](../). |

### Returvärde

true om objektet togs bort framgångsrikt från [`CosPdfDictionary`](../); annars false. Denna metod returnerar också false om objektet inte hittas i den ursprungliga [`CosPdfDictionary`](../).

### Se även

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


