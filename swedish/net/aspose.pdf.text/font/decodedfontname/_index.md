---
title: "Font.DecodedFontName"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Font egenskap. Ibland kan PDF-teckensnitt, vanligtvis kinesiska/japanska/koreanska teckensnitt, ha ett specifikt teckensnittsnamn. Detta namn är värdet för PDF-teckensnittsegenskapen BaseFont och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i oläslig form. För att få en läsbar form är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar avkodade teckensnittsnamnet, så använd den i fall där du stöter på ett oläsligt FontName. Om egenskapen FontName har en läsbar form kommer denna egenskap att vara densamma som FontName, så du kan använda den för alla fall där du behöver få teckensnittsnamnet i en läsbar form."
type: docs
weight: 20
url: /sv/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName property

Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet för PDF-teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i oläslig form. För att få en läsbar form är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar avkodade teckensnittsnamnet, så använd den i fall där du stöter på ett oläsligt [`FontName`](../fontname/). Om egenskapen [`FontName`](../fontname/) har en läsbar form kommer denna egenskap att vara densamma som [`FontName`](../fontname/), så du kan använda den för alla fall där du behöver få teckensnittsnamnet i en läsbar form.

```csharp
public string DecodedFontName { get; }
```

### Se även

* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


