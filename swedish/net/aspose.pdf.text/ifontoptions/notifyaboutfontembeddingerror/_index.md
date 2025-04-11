---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: IFontOptions-egenskap. Ibland är det inte möjligt att bädda in önskad teckensnitt i dokumentet. Det finns många anledningar, till exempel licensbegränsningar eller när önskat teckensnitt inte hittades på destinationsdatorn. När denna situation uppstår är det inte enkelt att upptäcka, eftersom önskat teckensnitt är inbäddat via en uppsättning egenskapsflagga Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den har ställts in, men det är inte en bekväm metod. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall när försök att bädda in teckensnitt misslyckades. Om denna flagga är inställd kommer ett undantag av typen [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) att kastas. Som standard false.
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError-egenskap

Ibland är det inte möjligt att bädda in önskad teckensnitt i dokumentet. Det finns många anledningar, till exempel licensbegränsningar eller när önskat teckensnitt inte hittades på destinationsdatorn. När denna situation uppstår är det inte enkelt att upptäcka, eftersom önskat teckensnitt är inbäddat via en uppsättning egenskapsflagga Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa denna egenskap omedelbart efter att den har ställts in, men det är inte en bekväm metod. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall när försök att bädda in teckensnitt misslyckades. Om denna flagga är inställd kommer ett undantag av typen [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) att kastas. Som standard false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Se Även

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)