---
title: "Delegat HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML-dokumentet. T.ex. om du vill göra CSS refererad i HTML t.ex. som otherPage.ASPXCssIDzjjkklj så måste en sådan anpassad strategi returnera otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5730
url: /sv/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML-dokumentet. T.ex. om du vill göra CSS refererad i HTML t.ex. som "otherPage.ASPX?CssID=zjjkklj" så måste en sådan anpassad strategi returnera "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | representerar en uppsättning data som kan användas för generering av CSS:s URL |

### Returvärde

måste returnera en sträng som representerar CSS:s URL eller URL-mall

### Se även

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


