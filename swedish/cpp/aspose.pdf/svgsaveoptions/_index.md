---
title: "Aspose::Pdf::SvgSaveOptions-klass"
linktitle: "SvgSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::SvgSaveOptions-klass. Sparalternativ för export till SVG-format i C++."
type: docs
weight: 17600
url: /sv/cpp/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class


Sparaalternativ för export till SVG-format.

```cpp
class SvgSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Nested classes

* Class [SvgImageSavingInfo](./svgimagesavinginfo/)
## Enums

| Enum | Beskrivning |
| --- | --- |
| [SvgExternalImageType](./svgexternalimagetype/) | uppräkningar av möjliga typer av bildfiler som kan sparas som externa resurser under [Pdf](../) till SVG-konvertering |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SvgSaveOptions](./svgsaveoptions/)() | Konstruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [EmbeddedImagesSavingStrategy](./embeddedimagessavingstrategy/) | Till en egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparning av en bild som extraherades från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. egen sparning till ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade SVG:n istället för den ursprungliga antagna sökvägen till bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' på variabeln 'imageSavingInfo' för parametern. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns. |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
