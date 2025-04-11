---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor metod. Tar bort elementet med den angivna nyckeln från DictionaryEditor
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
| key | Sträng | Nyckeln för elementet som ska tas bort. |

### Returvärde

Sant om elementet har tagits bort framgångsrikt; annars falskt. Denna metod returnerar också falskt om nyckeln inte hittades i den ursprungliga ordboken eller om nyckeln inte är redigerbar.

### Se Även

* klass [DictionaryEditor](../)
* namnrymd [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Tar bort den första förekomsten av ett specifikt objekt från [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Objektet som ska tas bort från [`DictionaryEditor`](../). |

### Returvärde

Sant om item har tagits bort framgångsrikt från [`DictionaryEditor`](../); annars falskt. Denna metod returnerar också falskt om item inte hittas i den ursprungliga [`DictionaryEditor`](../).

### Se Även

* gränssnitt [ICosPdfPrimitive](../../icospdfprimitive/)
* klass [DictionaryEditor](../)
* namnrymd [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)