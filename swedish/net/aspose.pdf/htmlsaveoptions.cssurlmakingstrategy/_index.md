---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML-dokumentet. T.ex. om du vill göra CSS refererad i HTML t.ex. som otherPage.ASPXCssIDzjjkklj Då måste en sådan anpassad strategi returnera otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /sv/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegat

Du kan tilldela denna egenskap en delegat skapad från en anpassad metod som implementerar skapandet av URL för CSS som refereras i det genererade HTML-dokumentet. T.ex. om du vill göra CSS refererad i HTML t.ex. som "otherPage.ASPX?CssID=zjjkklj" Då måste en sådan anpassad strategi returnera "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | representerar en uppsättning data som kan användas för generation av CSS' URL |

### Returvärde

måste returnera en sträng som representerar CSS's URL eller URL's mall

### Se Även

* klass [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)