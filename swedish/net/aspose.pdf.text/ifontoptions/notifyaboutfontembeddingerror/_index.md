---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IFontOptions‑egenskap. Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller att det önskade teckensnittet inte hittades på mål‑datorn. När denna situation uppstår är det inte enkelt att upptäcka eftersom det önskade teckensnittet är inbäddat via egendomsflaggan Font.IsEmbedded  true. Naturligtvis går det att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kastas ett undantag av typen FontEmbeddingException. Standardvärdet är falskt."
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller att det önskade teckensnittet inte hittades på mål‑datorn. När denna situation uppstår är det inte enkelt att upptäcka, eftersom det önskade teckensnittet är inbäddat via egendomsflaggan Font.IsEmbedded = true; Naturligtvis går det att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då ett försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kastas ett undantag av typen [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). Standardvärdet är falskt.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Se även

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


