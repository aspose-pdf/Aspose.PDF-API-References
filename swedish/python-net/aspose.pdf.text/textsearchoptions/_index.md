---
title: "TextSearchOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar alternativ för textsökning"
type: docs
weight: 460
url: /sv/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Representerar alternativ för textsökning

Typen TextSearchOptions visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Initierar en ny instans av klassen TextSearchOptions |
| TextSearchOptions(rectangle) | Initierar en ny instans av klassen TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Initierar en ny instans av klassen TextSearchOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_regular_expression_used | Hämtar eller anger indikation på att reguljärt uttryck används. |
| limit_to_page_bounds | Hämtar eller anger indikation på att text söks inom sidans gränser. |
| rectangle | Hämtar eller anger rektangel som begränsar den sökta texten. |
| use_font_engine_encoding | Hämtar eller anger indikation på att text kommer att sökas med font‑motor‑kodning.<br/>            true - betyder att font‑motor‑kodning kommer att användas (försök detta om textsökning misslyckas på grund av bristfällig kodning i dokumentet)<br/>            false - betyder att dokumentets fontkodning kommer att användas (standardvärde) |
| ignore_shadow_text | Hämtar eller anger indikation på att textfragment som representerar skugga av normal text kommer att ignoreras under sökning.<br/>            true - betyder att skuggtext inte kommer att hittas (försök detta om textsökning returnerar duplicerade fragment på nära positioner)<br/>            false - betyder att skuggtext kommer att hittas lika med normal text (standardvärde) |
| log_text_extraction_errors | Hämtar eller anger indikation på att fel vid textutvinning (avkodning) kommer att loggas i text‑ (fragment)‑absorbern.<br/>            true - betyder att fel vid textutvinning (avkodning) kommer att loggas. Det kan minska prestanda.<br/>            false (standard) - ingen fel‑loggning. |
| ignore_resource_font_errors | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras av text‑ (fragment)‑absorbern.<br/>            true - betyder att fel på grund av avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning.<br/>            false (standard) - fel på grund av avsaknad av teckensnitt kommer att avbryta bearbetning genom att kasta ett undantag. |
| search_for_text_related_graphics | Hämtar eller anger värde som tillåter sökning efter textrelaterad grafik (understrykning, bakgrund osv.) under textsökning.<br/>            true - sökning efter textrelaterad grafik kommer att utföras (standardvärde).<br/>            false - grafiska element som kan finnas i källdokumentet kommer att ignoreras. Ställ in detta vid prestandaproblem eller när det inte behövs att hantera understrykning, bakgrund eller beskärning. |
| stored_graphic_elements_max_count | Hämtar eller anger värde som begränsar sökning efter textrelaterad grafik (understrykning, bakgrund osv.) på en sida till det angivna antalet element.<br/>            Standardvärdet är 250. Ange ett lägre värde vid prestandaproblem, prova ett högre värde om vissa grafiska element inte hittades. |
| search_in_annotations | Hämtar eller anger värde som tillåter sökning efter text i Anmärkningar.<br/>            true - text kommer att sökas i Anmärkningar.<br/>            false - text i Anmärkningar kommer inte att parsas av TextFragmentAbsorber. |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

