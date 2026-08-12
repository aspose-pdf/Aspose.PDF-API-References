---
title: "Aspose::Pdf::Text::Font::get_DecodedFontName method"
linktitle: "get_DecodedFontName"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::Font::get_DecodedFontName method. Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet på PDF-teckensnittsegenskapen \"BaseFont\" och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i ett icke‑läsbart format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar avkodat teckensnittsnamn, så använd den i fall där du stöter på ett icke‑läsbart FontName. Om egenskapen FontName har ett läsbart format kommer denna egenskap att vara densamma som FontName, så du kan använda den för alla fall när du behöver få teckensnittsnamnet i ett läsbart format i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.text/font/get_decodedfontname/
---
## Font::get_DecodedFontName method


Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet för PDF-teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap representeras i hexadecimal form. Om man läser detta namn direkt kan det visas i ett oläsligt format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar det avkodade teckensnittsnamnet, så använd den i fall där du stöter på ett oläsligt [FontName](../). Om egenskapen [FontName](../) har ett läsbart format kommer denna egenskap att vara densamma som [FontName](../), så du kan använda den för alla fall där du behöver få teckensnittsnamnet i ett läsbart format.

```cpp
System::String Aspose::Pdf::Text::Font::get_DecodedFontName()
```

## Se även

* Class [String](../../../system/string/)
* Class [Font](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
