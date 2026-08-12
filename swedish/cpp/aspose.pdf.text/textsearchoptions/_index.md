---
title: "Aspose::Pdf::Text::TextSearchOptions klass"
linktitle: "TextSearchOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextSearchOptions klass. Representerar alternativ för textsökning i C++."
type: docs
weight: 5000
url: /sv/cpp/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class


Representerar alternativ för textsökning.

```cpp
class TextSearchOptions : public Aspose::Pdf::Text::TextOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Hämtar indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel på grund av avsaknad av teckensnitt kommer att ignoreras. [Text](../) segment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel på grund av avsaknad av teckensnitt kommer att avsluta bearbetningen genom att kasta ett undantag. |
| [get_IgnoreShadowText](./get_ignoreshadowtext/)() const | Hämtar indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner) false - betyder att skuggtext kommer att hittas liksom normal text (standardvärde). |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | Hämtar indikation på att reguljärt uttryck används. |
| [get_LimitToPageBounds](./get_limittopagebounds/)() const | Hämtar indikation på att text söks inom sidans gränser. |
| [get_LogTextExtractionErrors](./get_logtextextractionerrors/)() const | Hämtar indikation på att fel vid textutvinning (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textutvinning (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen felloggning. |
| [get_Rectangle](./get_rectangle/)() const | Hämtar rektangel som avgränsar den sökta texten. |
| [get_SearchForTextRelatedGraphics](./get_searchfortextrelatedgraphics/)() const | Hämtar värde som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund etc.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller om det inte behövs hantera understrykning, bakgrund eller beskärning. |
| [get_SearchInAnnotations](./get_searchinannotations/)() const | Hämtar värde som tillåter sökning efter text i [Annotations](../../aspose.pdf.annotations/). true - text kommer att sökas i [Annotations](../../aspose.pdf.annotations/). false - text i [Annotations](../../aspose.pdf.annotations/) kommer inte att parsas av [TextFragmentAbsorber](../textfragmentabsorber/). |
| [get_StoredGraphicElementsMaxCount](./get_storedgraphicelementsmaxcount/)() const | Hämtar värde som begränsar sökning efter textrelaterad grafik (understrykning, bakgrund etc.) på en sida till det angivna antalet element. Standardvärdet är 250. Sätt ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades. |
| [get_UseFontEngineEncoding](./get_usefontengineencoding/)() const | Hämtar indikation på att text kommer att sökas med teckensnittsmotorns kodning. true - betyder att teckensnittsmotorns kodning kommer att användas (prova detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet) false - betyder att dokumentets teckensnittskodning kommer att användas (standardvärde). |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Ställer in indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel på grund av avsaknad av teckensnitt kommer att ignoreras. [Text](../) segment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel på grund av avsaknad av teckensnitt kommer att avsluta bearbetningen genom att kasta ett undantag. |
| [set_IgnoreShadowText](./set_ignoreshadowtext/)(bool) | Ställer in indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner) false - betyder att skuggtext kommer att hittas liksom normal text (standardvärde). |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | Ställer in indikation på att reguljärt uttryck används. |
| [set_LimitToPageBounds](./set_limittopagebounds/)(bool) | Ställer in indikation på att text söks inom sidans gränser. |
| [set_LogTextExtractionErrors](./set_logtextextractionerrors/)(bool) | Ställer in indikation på att fel vid textutvinning (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textutvinning (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen felloggning. |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in rektangel som avgränsar den sökta texten. |
| [set_SearchForTextRelatedGraphics](./set_searchfortextrelatedgraphics/)(bool) | Ställer in värde som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund etc.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller om det inte behövs hantera understrykning, bakgrund eller beskärning. |
| [set_SearchInAnnotations](./set_searchinannotations/)(bool) | Ställer in värde som tillåter sökning efter text i [Annotations](../../aspose.pdf.annotations/). true - text kommer att sökas i [Annotations](../../aspose.pdf.annotations/). false - text i [Annotations](../../aspose.pdf.annotations/) kommer inte att parsas av [TextFragmentAbsorber](../textfragmentabsorber/). |
| [set_StoredGraphicElementsMaxCount](./set_storedgraphicelementsmaxcount/)(int32_t) | Ställer in värde som begränsar sökning efter textrelaterad grafik (understrykning, bakgrund etc.) på en sida till det angivna antalet element. Standardvärdet är 250. Sätt ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades. |
| [set_UseFontEngineEncoding](./set_usefontengineencoding/)(bool) | Ställer in indikation på att text kommer att sökas med teckensnittsmotorns kodning. true - betyder att teckensnittsmotorns kodning kommer att användas (prova detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet) false - betyder att dokumentets teckensnittskodning kommer att användas (standardvärde). |
| [TextSearchOptions](./textsearchoptions/)(bool) | Initierar en ny instans av objektet [TextSearchOptions](./). Anger läge för användning av reguljära uttryck. |
| [TextSearchOptions](./textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Initierar en ny instans av objektet [TextSearchOptions](./). Anger rektangel som avgränsar den sökta texten. |
| [TextSearchOptions](./textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) | Initierar en ny instans av objektet [TextSearchOptions](./). Anger rektangel som avgränsar den sökta texten och läge för användning av reguljära uttryck. |
## Se även

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
