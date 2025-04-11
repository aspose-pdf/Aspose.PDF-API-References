---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions klass. Representerar alternativ för textsökning
type: docs
weight: 11040
url: /sv/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions klass

Representerar alternativ för textsökning

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Initierar en ny instans av `TextSearchOptions` objektet. Anger läget för användning av reguljära uttryck. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Initierar en ny instans av `TextSearchOptions` objektet. Anger rektangel som avgränsar den sökta texten. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Initierar en ny instans av `TextSearchOptions` objektet. Anger rektangel som avgränsar den sökta texten och läget för användning av reguljära uttryck. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Hämtar eller sätter indikation att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text (fragment) absorberaren. true - betyder att fel av avsaknad av teckensnitt kommer att ignoreras. Textsegment som hänvisar till felaktiga resurser kommer att hoppas över under bearbetning. false (standard) - avsaknad av teckensnitt fel kommer att avsluta bearbetningen genom att kasta ett undantag. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Hämtar eller sätter indikation att textfragment som representerar skugga av normal text kommer att ignoreras under sökningen. true - betyder att skugga text inte kommer att hittas (försök detta om textsökningen returnerar duplicerade fragment på nära positioner) false - betyder att skugga text kommer att hittas liksom normal text (standardvärde) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Hämtar eller sätter indikation att reguljära uttryck används. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Hämtar eller sätter indikation att text söks inom sidgränserna. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Hämtar eller sätter indikation att fel vid textutvinning (avkodning) kommer att loggas i text (fragment) absorberaren. true - betyder att fel vid textutvinning (avkodning) kommer att loggas. Det kan minska prestanda. false (standard) - ingen fel loggning. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Hämtar eller sätter rektangel som avgränsar den sökta texten. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Hämtar eller sätter värde som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund etc.) under textsökning. true - sökning efter textrelaterad grafik kommer att utföras (standardvärde). false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Sätt detta vid prestandaproblem eller om det inte behövs att hantera understrykning, bakgrund eller beskärning. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Hämtar eller sätter värde som tillåter sökning efter text i Anmärkningar. true - text kommer att sökas i Anmärkningar. false - text i Anmärkningar kommer inte att tolkas av TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Hämtar eller sätter värde som begränsar sökningen efter textrelaterad grafik (understrykning, bakgrund etc.) på en sida för det angivna antalet element. Standard är 250. Sätt ett lägre värde vid prestandaproblem, försök med ett större värde om vissa grafiska element inte hittades. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Hämtar eller sätter indikation att text kommer att sökas med hjälp av teckensnitts motor kodning. true - betyder att teckensnitts motor kodning kommer att användas (försök detta om textsökningen misslyckas på grund av ofullständig kodning i dokumentet) false - betyder att dokumentets teckensnitts kodning kommer att användas (standardvärde) |

### Se Även

* klass [TextOptions](../textoptions/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* samling [Aspose.PDF](../../)