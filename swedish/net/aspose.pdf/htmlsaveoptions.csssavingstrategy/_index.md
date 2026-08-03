---
title: "Delegat HtmlSaveOptions.CssSavingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Du kan tilldela den här egenskapen en anpassad strategi som implementerar bearbetning och/eller sparande av en CSS‑del som skapades under konvertering från PDF till HTML. I sådant fall måste bearbetning, såsom sparande till ström eller disk, göras i den anpassade koden."
type: docs
weight: 5720
url: /sv/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

Du kan tilldela den här egenskapen en anpassad strategi som implementerar bearbetning och/eller sparande av en CSS‑del som skapades under konvertering från PDF till HTML. I sådant fall måste bearbetning (som sparande till ström eller disk) göras i den anpassade koden.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | representerar en uppsättning data som kan användas för att spara den levererade CSS-delen |

### Se även

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


