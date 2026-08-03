---
title: "DictionaryEditor.Remove"
second_title: "Aspose.PDF för .NET API‑referens"
description: "DictionaryEditor metod. Tar bort elementet med den angivna nyckeln från DictionaryEditor"
type: docs
weight: 140
url: /sv/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Tar bort elementet med den angivna nyckeln från [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Nyckeln för elementet som ska tas bort. |

### Returvärde

True om elementet har tagits bort framgångsrikt; annars false. Denna metod returnerar också false om nyckeln inte hittades i den ursprungliga ordboken eller nyckeln inte är redigerbar

### Se även

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Tar bort den första förekomsten av ett specifikt objekt från [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Objektet att ta bort från [`DictionaryEditor`](../). |

### Returvärde

true om objektet framgångsrikt togs bort från [`DictionaryEditor`](../); annars false. Denna metod returnerar också false om objektet inte hittas i den ursprungliga [`DictionaryEditor`](../).

### Se även

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


