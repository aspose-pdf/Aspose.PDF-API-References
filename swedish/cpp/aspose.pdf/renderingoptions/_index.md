---
title: "Aspose::Pdf::RenderingOptions-klass"
linktitle: "RenderingOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::RenderingOptions-klass. Representerar renderingsalternativ i C++."
type: docs
weight: 16400
url: /sv/cpp/aspose.pdf/renderingoptions/
---
## RenderingOptions class


Representerar renderingsalternativ.

```cpp
class RenderingOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AnalyzeFonts](./get_analyzefonts/)() const | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Teckensnittssubstitutionsalgoritmen följer dessa steg: |
| [get_BarcodeOptimization](./get_barcodeoptimization/)() const | Hämtar streckkodoptimeringsläge. |
| [get_ConvertFontsToUnicodeTTF](./get_convertfontstounicodettf/)() const | Indikerar att alla typsnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera typsnittsbruk, eftersom varje nytt TTF-typsnitt endast innehåller de symboler som används i texten, inte alla symboler från källtypsnittet. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Hämtar/anger standardnamnet på typsnitt som används för att ersätta saknade typsnitt. |
| [get_HeightExtraUnits](./get_heightextraunits/)() const | Hämtar ett värde som används för att öka eller minska rektangelns bredd för AppendRectangle-operatorn. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Hämtar indikation på att fel relaterade till avsaknad av teckensnitt kommer att ignoreras. true – betyder att fel på grund av avsaknad av teckensnitt ignoreras. [Text](../../aspose.pdf.text/)-segment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [get_InterpolationHighQuality](./get_interpolationhighquality/)() const | Hämtar högkvalitetsläge för interpolering. |
| [get_MaxFontsCacheSize](./get_maxfontscachesize/)() const | Maximalt antal typsnitt i typsnittscache. Standardvärdet är 10. |
| [get_MaxSymbolsCacheSize](./get_maxsymbolscachesize/)() const | Maximalt antal symboler i symbolcache. Standardvärdet är 100. |
| [get_OptimizeDimensions](./get_optimizedimensions/)() const | Hämtar optimeringsläget för dimensioner. |
| [get_ScaleImagesToFitPageWidth](./get_scaleimagestofitpagewidth/)() const | Hämtar ett värde som används för att skala alla bilder på sidan så att de passar sidans bredd. |
| [get_SystemFontsNativeRendering](./get_systemfontsnativerendering/)() const | Hämtar ett läge där systemtypsnitt renderas nativt. |
| [get_UseFontHinting](./get_usefonthinting/)() const | Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen av ett konturtypsnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande har användning av denna flagga bara effekt för TTF-typsnitt, om dessa typsnitt används i källdokumentet. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Hämtar en flagga som bestämmer om den nya bildbehandlingsmotorn används eller inte. |
| [get_WidthExtraUnits](./get_widthextraunits/)() const | Hämtar ett värde som används för att öka eller minska rektangelns bredd för AppendRectangle-operatorn. |
| [RenderingOptions](./renderingoptions/)() | Initierar en ny instans av objektet [RenderingOptions](./). |
| [set_AnalyzeFonts](./set_analyzefonts/)(bool) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Teckensnittssubstitutionsalgoritmen följer dessa steg: |
| [set_BarcodeOptimization](./set_barcodeoptimization/)(bool) | Ställer in streckkodoptimeringsläge. |
| [set_ConvertFontsToUnicodeTTF](./set_convertfontstounicodettf/)(bool) | Indikerar att alla typsnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera typsnittsbruk, eftersom varje nytt TTF-typsnitt endast innehåller de symboler som används i texten, inte alla symboler från källtypsnittet. |
| [set_DefaultFontName](./set_defaultfontname/)(const System::String\&) | Hämtar/anger standardnamnet på typsnitt som används för att ersätta saknade typsnitt. |
| [set_HeightExtraUnits](./set_heightextraunits/)(float) | Ställer in ett värde som används för att öka eller minska rektangelns bredd för AppendRectangle‑operatorn. |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Ställer in indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel på grund av avsaknad av teckensnitt ignoreras. [Text](../../aspose.pdf.text/)-segment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [set_InterpolationHighQuality](./set_interpolationhighquality/)(bool) | Ställer in högkvalitetsläge för interpolering. |
| [set_MaxFontsCacheSize](./set_maxfontscachesize/)(int32_t) | Maximalt antal typsnitt i typsnittscache. Standardvärdet är 10. |
| [set_MaxSymbolsCacheSize](./set_maxsymbolscachesize/)(int32_t) | Maximalt antal symboler i symbolcache. Standardvärdet är 100. |
| [set_OptimizeDimensions](./set_optimizedimensions/)(bool) | Ställer in läge för optimering av dimensioner. |
| [set_ScaleImagesToFitPageWidth](./set_scaleimagestofitpagewidth/)(bool) | Ställer in ett värde som används för att skala alla bilder på sidan så att de passar sidans bredd. |
| [set_SystemFontsNativeRendering](./set_systemfontsnativerendering/)(bool) | Ställer in ett läge där systemteckensnitt renderas nativt. |
| [set_UseFontHinting](./set_usefonthinting/)(bool) | Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen av ett konturtypsnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande har användning av denna flagga bara effekt för TTF-typsnitt, om dessa typsnitt används i källdokumentet. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Ställer in en flagga som bestämmer om den nya bildbehandlingsmotorn används eller inte. |
| [set_WidthExtraUnits](./set_widthextraunits/)(float) | Ställer in ett värde som används för att öka eller minska rektangelns bredd för AppendRectangle‑operatorn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
