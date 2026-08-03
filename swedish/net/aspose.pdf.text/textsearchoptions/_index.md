---
title: "Klass TextSearchOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextSearchOptions klass. Representerar alternativ för textsökning"
type: docs
weight: 11230
url: /sv/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

Representerar alternativ för textsökning

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Initierar en ny instans av `TextSearchOptions`-objektet. Anger läge för användning av reguljära uttryck. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Initierar en ny instans av `TextSearchOptions`-objektet. Anger rektangel som avgränsar den sökta texten. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Initierar en ny instans av `TextSearchOptions`-objektet. Anger rektangel som avgränsar den sökta texten och läge för användning av reguljära uttryck. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras av text (fragment) absorberaren. true - betyder att fel på avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - fel om avsaknad av teckensnitt avslutar bearbetningen genom att kasta ett undantag. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Hämtar eller anger indikation på att textfragment som representerar skuggan av normal text ska ignoreras under sökning. true - betyder att skuggtext inte kommer att hittas (prova detta om textsökning returnerar duplicerade fragment på nära positioner). false - betyder att skuggtext kommer att hittas lika med normal text (standardvärde). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Hämtar eller anger indikation på att reguljärt uttryck används. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Hämtar eller anger indikation på att text söks inom sidans gränser. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Hämtar eller anger indikation på att fel vid textutvinning (avkodning) ska loggas i text (fragment) absorberaren. true - betyder att fel vid textutvinning (avkodning) kommer att loggas. Detta kan minska prestandan. false (standard) - ingen felloggning. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Hämtar eller anger rektangeln som omger den sökta texten. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Hämtar eller anger värdet som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund osv.) under textsökning. true – sökning efter textrelaterad grafik kommer att utföras (standardvärde). false – grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller när det inte behövs att hantera understrykning, bakgrund eller beskärning. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Hämtar eller anger värdet som tillåter sökning efter text i Annotations. true – text kommer att sökas i Annotations. false – text i Annotations kommer inte att parsas av TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Hämtar eller anger värdet som begränsar sökning efter textrelaterad grafik (understrykning, bakgrund osv.) på en sida för det angivna antalet element. Standardvärdet är 250. Ange ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Hämtar eller anger indikation på att text kommer att sökas med teckensnittsmotorns kodning. true – betyder att teckensnittsmotorns kodning kommer att användas (försök detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet). false – betyder att dokumentets teckensnittskodning kommer att användas (standardvärde). |

### Se även

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


