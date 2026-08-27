---
title: "RenderingOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar renderingsalternativ."
type: docs
weight: 1330
url: /sv/python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

Representerar renderingsalternativ.

RenderingOptions-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| RenderingOptions() | Initierar en ny instans av RenderingOptions-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| barcode_optimization | Hämtar eller anger läge för streckkodoptimering. |
| optimize_dimensions | Hämtar eller anger läge för optimering av dimensioner. |
| system_fonts_native_rendering | Hämtar eller anger ett läge där systemteckensnitt renderas nativt. |
| use_new_imaging_engine | Hämtar eller anger en flagga som bestämmer om den nya bildbehandlingsmotorn används eller inte. |
| width_extra_units | Hämtar eller anger ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| height_extra_units | Hämtar eller anger ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| convert_fonts_to_unicode_ttf | Indikerar att alla teckensnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart för kompatibilitet <br/>             skäl och för att optimera teckensnittsanvändning, eftersom varje nytt TTF-teckensnitt inte kommer att ha alla symboler <br/>             från källteckensnittet, utan endast de symboler som används i texten. |
| use_font_hinting | Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen <br/>            av ett konturteckensnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. <br/>            För närvarande kan användning av denna flagga endast ha effekt för TTF-teckensnitt, om dessa teckensnitt används i källdokumentet. |
| scale_images_to_fit_page_width | Hämtar eller anger ett värde som används för att skala alla bilder på sidan så att de passar sidans bredd. |
| interpolation_high_quality | Hämtar eller anger högkvalitetsläge för interpolering. |
| max_fonts_cache_size | Maximalt antal teckensnitt i teckensnittscache. Standardvärdet är 10. |
| max_symbols_cache_size | Maximalt antal symboler i symbolcachen. Standardvärdet är 100. |
| default_font_name | Hämtar/sätter standardnamnet på teckensnitt som används för att ersätta saknade teckensnitt. |
| ignore_resource_font_errors | Hämtar eller sätter indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras.<br/>            true - betyder att fel av avsaknad av teckensnitt kommer att ignoreras. Textsegment som refererar till felaktiga resurser kommer att hoppas över under bearbetning.<br/>            false som standard |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

