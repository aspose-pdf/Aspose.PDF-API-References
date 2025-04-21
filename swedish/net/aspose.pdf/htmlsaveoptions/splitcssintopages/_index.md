---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions-egenskap. När multipagemode är valt, det vill säga SplitIntoPages är sant, definierar denna attribut huruvida en separat CSS-fil ska skapas för varje resultat HTML-sida. Som standard är denna attribut falsk, så en stor gemensam CSS kommer att skapas för alla skapade sidor. Sammanfattningsstorleken av alla CSSer som genereras i detta läge är vanligtvis mycket mer än storleken på en stor CSS-fil, eftersom CSS-klasser i det tidigare fallet är dubbletter i flera CSS-filer för varje sida. Så, denna inställning är sämre att använda endast när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därför är storleken på CSS för varje enskild sida det mest kritiska problemet.
type: docs
weight: 190
url: /sv/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages-egenskap

När multipage-mode är valt (det vill säga 'SplitIntoPages' är 'true'), definierar denna attribut huruvida en separat CSS-fil ska skapas för varje resultat HTML-sida. Som standard är denna attribut falsk, så en stor gemensam CSS kommer att skapas för alla skapade sidor. Sammanfattningsstorleken av alla CSS:er som genereras i detta läge (en CSS per sida) är vanligtvis mycket mer än storleken på en stor CSS-fil, eftersom CSS-klasser i det tidigare fallet är dubbletter i flera CSS-filer för varje sida. Så, denna inställning är sämre att använda endast när du är intresserad av framtida bearbetning av varje HTML-sida oberoende, och därför är storleken på CSS för varje enskild sida det mest kritiska problemet.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Se Även

* klass [HtmlSaveOptions](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)