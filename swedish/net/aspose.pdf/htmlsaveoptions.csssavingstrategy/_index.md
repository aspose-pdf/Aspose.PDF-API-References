---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Du kan tilldela denna egenskap en anpassad strategi som implementerar bearbetning och/eller sparande av en del av CSS som skapades under konverteringen av PDF till HTML. I sådana fall måste bearbetning (som att spara till ström eller disk) göras i den anpassade koden
type: docs
weight: 5590
url: /sv/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy-delegat

Du kan tilldela denna egenskap en anpassad strategi som implementerar bearbetning och/eller sparande av en del av CSS som skapades under konverteringen av PDF till HTML. I sådana fall måste bearbetning (som att spara till ström eller disk) göras i den anpassade koden

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | representerar en uppsättning data som kan användas för att spara den angivna CSS-delen |

### Se Även

* klass [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)