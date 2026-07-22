---
title: "Aspose::Pdf::SaveOptions klass"
linktitle: "SaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::SaveOptions klass. SaveOptions‑typen håller en abstraheringsnivå för individuella sparalternativ i C++."
type: docs
weight: 17200
url: /sv/cpp/aspose.pdf/saveoptions/
---
## SaveOptions class


[SaveOptions](./) type hold level of abstraction on individual save options.

```cpp
class SaveOptions : public virtual System::Object
```

## Nested classes

* Class [BorderInfo](./borderinfo/)
* Class [BorderPartStyle](./borderpartstyle/)
* Class [MarginInfo](./margininfo/)
* Class [MarginPartStyle](./marginpartstyle/)
* Class [ResourceSavingInfo](./resourcesavinginfo/)
## Enums

| Enum | Beskrivning |
| --- | --- |
| [HtmlBorderLineType](./htmlborderlinetype/) | Representerar linjetyper som kan användas i resultatsdokumentet för att rita kanter eller andra linjer. |
| [NodeLevelResourceType](./nodelevelresourcetype/) | enumererar möjliga typer av sparade externa resurser |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CacheGlyphs](./get_cacheglyphs/)() const | Hämtar booleskt värde som indikerar om teckenglyfer kommer att cachas medan APS‑sidor förbereds. Förbättrar prestanda vid konvertering av PDF till andra format men ökar minnesanvändningen. |
| [get_CloseResponse](./get_closeresponse/)() const | Hämtar booleskt värde som indikerar om Response‑objektet kommer att stängas efter att dokumentet sparats i svaret. |
| [get_SaveFormat](./get_saveformat/)() const | Format för datasparning. |
| [get_WarningHandler](./get_warninghandler/)() const | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar [ReturnAction](../returnaction/) enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, i så fall ska Save‑operationen avbrytas. |
| [SaveOptions](./saveoptions/)() |  |
| [set_CacheGlyphs](./set_cacheglyphs/)(bool) | Ställer in booleskt värde som indikerar om teckenglyfer kommer att cachas medan APS‑sidor förbereds. Förbättrar prestanda vid konvertering av PDF till andra format men ökar minnesanvändningen. |
| [set_CloseResponse](./set_closeresponse/)(bool) | Ställer in booleskt värde som indikerar om Response‑objektet kommer att stängas efter att dokumentet sparats i svaret. |
| [set_WarningHandler](./set_warninghandler/)(const System::SharedPtr\<IWarningCallback\>\&) | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar [ReturnAction](../returnaction/) enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, i så fall ska Save‑operationen avbrytas. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
