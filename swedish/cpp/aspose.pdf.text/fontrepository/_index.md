---
title: "Aspose::Pdf::Text::FontRepository klass"
linktitle: "FontRepository"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::FontRepository klass. Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard Pdf-teckensnitt. Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.pdf.text/fontrepository/
---
## FontRepository class


Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard [Pdf](../../aspose.pdf/) teckensnitt. Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt.

```cpp
class FontRepository : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [FindFont](./findfont/)(const System::String\&) | Söker och returnerar teckensnitt med angivet teckensnittsnamn. |
| static [FindFont](./findfont/)(const System::String\&, bool) | Söker och returnerar teckensnitt med angivet teckensnittsnamn, ignorerar eller beaktar skiftlägeskänslighet. |
| static [FindFont](./findfont/)(const System::String\&, FontStyles) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil. |
| static [FindFont](./findfont/)(const System::String\&, FontStyles, bool) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil, ignorerar eller beaktar skiftlägeskänslighet. |
| static [get_Sources](./get_sources/)() | Hämtar samling av teckensnittskällor. |
| static [get_Substitutions](./get_substitutions/)() | Hämtar samling av teckensnittssubstitutionsstrategier. |
| static [LoadFonts](./loadfonts/)() | Laddar systeminstallerade teckensnitt och standard [Pdf](../../aspose.pdf/) teckensnitt. Denna metod är utformad för att påskynda teckensnittsladdningsprocessen. Som standard laddas teckensnitt vid första begäran om något teckensnitt. Användning av denna metod laddar system- och standard [Pdf](../../aspose.pdf/) teckensnitt omedelbart innan något [Pdf](../../aspose.pdf/) dokument öppnas. |
| static [OpenFont](./openfont/)(const System::SharedPtr\<System::IO::Stream\>\&, const FontTypes\&) | Öppnar teckensnitt med angiven teckensnittström. |
| static [OpenFont](./openfont/)(const System::String\&) | Öppnar teckensnitt med angiven teckensnittsfilssökväg. |
| static [OpenFont](./openfont/)(const System::String\&, const System::String\&) | Öppnar teckensnitt med angiven teckensnittsfilssökväg och metrisfilssökväg. |
| static [ReloadFonts](./reloadfonts/)() | Laddar om alla teckensnitt som anges av egenskapen [Sources](../) |


## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
