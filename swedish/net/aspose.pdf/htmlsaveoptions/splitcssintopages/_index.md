---
title: "HtmlSaveOptions.SplitCssIntoPages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "HtmlSaveOptions egenskap. När flersidigt läge är valt, d.v.s. SplitIntoPages är sant, definierar detta attribut om en separat CSS‑fil ska skapas för varje resultat‑HTML‑sida. Som standard är detta attribut falskt, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS‑filer som genereras i detta läge – en CSS per sida – är vanligtvis mycket större än storleken på en enda stor CSS‑fil eftersom i det första fallet dupliceras CSS‑klasser i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida oberoende och därför är storleken på CSS för varje enskild sida den mest kritiska frågan."
type: docs
weight: 190
url: /sv/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

När flersidigt läge är valt (dvs. 'SplitIntoPages' är 'true'), definierar detta attribut om en separat CSS-fil ska skapas för varje resulterande HTML-sida. Som standard är detta attribut false, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS-filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS-fil, eftersom i det första fallet är CSS-klasser duplicerade i flera CSS-filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av att bearbeta varje HTML-sida separat i framtiden, och därför är storleken på CSS för varje enskild sida det mest kritiska problemet.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Se även

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


