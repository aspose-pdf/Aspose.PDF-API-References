---
title: "CosPdfDictionary.TryGetValue"
second_title: "Aspose.PDF för .NET API‑referens"
description: "CosPdfDictionary‑metod. För åtkomst till enkla datatyper som sträng, namn, bool, nummer. Returnerar null för andra typer."
type: docs
weight: 170
url: /sv/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue method

För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Nyckelvärde |
| value | ICosPdfPrimitive& | returnerar [`ICosPdfPrimitive`](../../icospdfprimitive/) för nyckeln eller null. |

### Returvärde

Returnerar true om [`ICosPdfPrimitive`](../../icospdfprimitive/) är av typen string, name, bool, number. Returnerar false för alla andra typer.

### Se även

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


