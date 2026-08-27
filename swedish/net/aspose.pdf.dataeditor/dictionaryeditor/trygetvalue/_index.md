---
title: "DictionaryEditor.TryGetValue"
second_title: "Aspose.PDF för .NET API‑referens"
description: "DictionaryEditor‑metod. För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer"
type: docs
weight: 150
url: /sv/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue method

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
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


