---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary-egenskap. Hämtar eller ställer in elementet med den angivna nyckeln
type: docs
weight: 60
url: /sv/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary indexer

Hämtar eller ställer in elementet med den angivna nyckeln.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| key | Nyckeln för elementet som ska hämtas eller ställas in. |

### Returvärde

Elementet med den angivna nyckeln.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Nyckeln är null. |
| KeyNotFoundException | Egenskapen hämtas och nyckeln hittas inte. |
| ArgumentException | Utlöser undantag om nyckeln inte kan redigeras/ställas in. |

### Se Även

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)