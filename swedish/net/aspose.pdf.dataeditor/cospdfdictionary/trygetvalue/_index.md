---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary-metod. För åtkomst till enkla datatyper som sträng, namn, bool, nummer. Returnerar null för andra typer
type: docs
weight: 170
url: /sv/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue metod

För åtkomst till enkla datatyper som sträng, namn, bool, nummer. Returnerar null för andra typer.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | Sträng | Nyckelvärde |
| value | ICosPdfPrimitive& | returnerar [`ICosPdfPrimitive`](../../icospdfprimitive/) för nyckel eller null. |

### Returvärde

Returnerar true om [`ICosPdfPrimitive`](../../icospdfprimitive/) är som sträng, namn, bool, nummer. Returnerar false för alla andra typer.

### Se Även

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)