---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Teckensnittsegenskap. Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha specifika teckensnittsnamn. Detta namn är värdet av PDF-teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap representeras i hexadecimalt format. Om man läser detta namn direkt kan det representeras i oläsligt format. För att få läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler specifika för detta teckensnitt. Denna egenskap returnerar det avkodade teckensnittsnamnet, så använd det i fall när du stöter på ett oläsligt [`FontName`](../fontname/). Om egenskapen [`FontName`](../fontname/) har läsbart format kommer denna egenskap att vara densamma som [`FontName`](../fontname/), så du kan använda denna egenskap i alla fall när du behöver få teckensnittsnamnet i ett läsbart format.
type: docs
weight: 20
url: /sv/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName-egenskap

Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha specifika teckensnittsnamn. Detta namn är värdet av PDF-teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap representeras i hexadecimalt format. Om man läser detta namn direkt kan det representeras i oläsligt format. För att få läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler specifika för detta teckensnitt. Denna egenskap returnerar det avkodade teckensnittsnamnet, så använd det i fall när du stöter på ett oläsligt [`FontName`](../fontname/). Om egenskapen [`FontName`](../fontname/) har läsbart format kommer denna egenskap att vara densamma som [`FontName`](../fontname/), så du kan använda denna egenskap i alla fall när du behöver få teckensnittsnamnet i ett läsbart format.

```csharp
public string DecodedFontName { get; }
```

### Se Även

* klass [Font](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../../)