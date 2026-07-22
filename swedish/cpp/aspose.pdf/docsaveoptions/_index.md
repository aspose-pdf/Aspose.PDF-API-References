---
title: "Aspose::Pdf::DocSaveOptions klass"
linktitle: "DocSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocSaveOptions klass. Sparaalternativ för export till Doc-format i C++."
type: docs
weight: 3800
url: /sv/cpp/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class


Spara alternativ för export till Doc-format.

```cpp
class DocSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [DocFormat](./docformat/) | Tillåter att ange .doc- eller .docx-filformat. |
| [RecognitionMode](./recognitionmode/) | Gör det möjligt att kontrollera hur ett PDF-dokument konverteras till ett ordbehandlingsdokument. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DocSaveOptions](./docsaveoptions/)() | Konstruktor. |
| [get_AddReturnToLineEnd](./get_addreturntolineend/)() const | Använd stycke- eller radbrytningar. |
| [get_BatchSize](./get_batchsize/)() override | Definierar batch‑storlek om batch‑konvertering är tillämplig för käll‑ och destinationsformatparet. |
| [get_ConvertType3Fonts](./get_converttype3fonts/)() const | Hämtar konvertering för Type3-teckensnitt. I Type 3-teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Detta innebär att i DOC/DOCX-utdata ser vi bilder istället för text. Sätt detta flagg till true för att konvertera Type3-teckensnitt till TTF och få text i den resulterande filen. |
| [get_Format](./get_format/)() const | Utdataformat. |
| [get_ImageResolutionX](./get_imageresolutionx/)() const | Konverterade bilder X-upplösning. |
| [get_ImageResolutionY](./get_imageresolutiony/)() const | Konverterade bilder Y-upplösning. |
| [get_MaxDistanceBetweenTextLines](./get_maxdistancebetweentextlines/)() const | Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av textradernas höjd. |
| [get_MemorySaveModePath](./get_memorysavemodepath/)() const | Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data vid konvertering i minneslagringsläge. |
| [get_Mode](./get_mode/)() const | Identifieringsläge. |
| [get_RecognizeBullets](./get_recognizebullets/)() const | Aktivera identifiering av punktlistor. |
| [get_RelativeHorizontalProximity](./get_relativehorizontalproximity/)() const | I [Pdf](../) kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste vi ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord under identifiering av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst lika brett mellan bokstäver innebär att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast i fall då käll‑PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så i de allra flesta fall förändrar denna parameter ingenting i det resulterande dokumentet. |
| [get_ReSaveFonts](./get_resavefonts/)() const | Hämtar proceduren för att spara om teckensnitt. Om den är satt till true laddar vi om teckensnitt på varje sida för att undvika påverkan från tidigare teckensnittsegenskaper och laddar det nyss skapade teckensnittet från början. Ställ in detta alternativ till false om du vill förbättra prestandan. Standardvärdet är true;. |
| [set_AddReturnToLineEnd](./set_addreturntolineend/)(bool) | Använd stycke- eller radbrytningar. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Definierar batch‑storlek om batch‑konvertering är tillämplig för käll‑ och destinationsformatparet. |
| [set_ConvertType3Fonts](./set_converttype3fonts/)(bool) | Ställer in konvertering för Type3-teckensnitt. I Type 3-teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Detta innebär att i DOC/DOCX-utdata ser vi bilder istället för text. Ställ in denna flagga till true för att konvertera Type3-teckensnitt till TTF och få text i den resulterande filen. |
| [set_Format](./set_format/)(DocSaveOptions::DocFormat) | Utdataformat. |
| [set_ImageResolutionX](./set_imageresolutionx/)(int32_t) | Konverterade bilder X-upplösning. |
| [set_ImageResolutionY](./set_imageresolutiony/)(int32_t) | Konverterade bilder Y-upplösning. |
| [set_MaxDistanceBetweenTextLines](./set_maxdistancebetweentextlines/)(float) | Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av textradernas höjd. |
| [set_MemorySaveModePath](./set_memorysavemodepath/)(const System::String\&) | Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data vid konvertering i minneslagringsläge. |
| [set_Mode](./set_mode/)(DocSaveOptions::RecognitionMode) | Identifieringsläge. |
| [set_RecognizeBullets](./set_recognizebullets/)(bool) | Aktivera identifiering av punktlistor. |
| [set_RelativeHorizontalProximity](./set_relativehorizontalproximity/)(float) | I [Pdf](../) kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste vi ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord under identifiering av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst lika brett mellan bokstäver innebär att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast i fall då käll‑PDF innehåller specifika sällan använda teckensnitt för vilka det optimala värdet inte kan beräknas från teckensnittet. Så i de allra flesta fall förändrar denna parameter ingenting i det resulterande dokumentet. |
| [set_ReSaveFonts](./set_resavefonts/)(bool) | Ställer in proceduren för att spara om teckensnitt. Om den är satt till true laddar vi om teckensnitt på varje sida för att undvika påverkan från tidigare teckensnittsegenskaper och laddar det nyss skapade teckensnittet från början. Ställ in detta alternativ till false om du vill förbättra prestandan. Standardvärdet är true;. |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
