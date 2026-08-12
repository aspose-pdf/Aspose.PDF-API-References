---
title: "Aspose::Pdf::AutoTaggingSettings class"
linktitle: "AutoTaggingSettings"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::AutoTaggingSettings class. Tillhandahåller inställningar för automatisk taggning i PDF-dokument i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf/autotaggingsettings/
---
## AutoTaggingSettings class


Tillhandahåller inställningar för den automatiska taggningfunktionen i PDF‑dokument.

```cpp
class AutoTaggingSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AutoTaggingSettings](./autotaggingsettings/)() |  |
| static [get_Default](./get_default/)() | Hämtar standardinställningarna för automatisk taggning i PDF-dokument. |
| [get_EnableAutoTagging](./get_enableautotagging/)() const | Hämtar ett värde som indikerar om den automatiska taggningsfunktionen är aktiverad. |
| [get_HeadingLevels](./get_headinglevels/)() const | Hämtar rubriknivåerna som används för att bestämma strukturen av rubriker i ett PDF-dokument. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Hämtar strategin som används för att känna igen rubriker i dokumentet under automatisk taggning. |
| [set_EnableAutoTagging](./set_enableautotagging/)(bool) | Ställer in ett värde som indikerar om den automatiska taggningsfunktionen är aktiverad. |
| [set_HeadingLevels](./set_headinglevels/)(const System::SharedPtr\<Aspose::Pdf::HeadingLevels\>\&) | Ställer in rubriknivåerna som används för att bestämma strukturen för rubriker i ett PDF-dokument. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::HeadingRecognitionStrategy) | Ställer in strategin som används för att känna igen rubriker i dokumentet under automatisk taggning. |
## Anmärkningar


Klassen [AutoTaggingSettings](./) möjliggör konfiguration av alternativ för automatisk taggning av PDF-innehåll. Den inkluderar egenskaper för att aktivera eller inaktivera automatisk taggning, specificera en strategi för rubrikigenkänning och definiera rubriknivåer baserat på teckenstorlekar.
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
