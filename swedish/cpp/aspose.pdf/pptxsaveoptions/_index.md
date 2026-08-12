---
title: "Aspose::Pdf::PptxSaveOptions klass"
linktitle: "PptxSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PptxSaveOptions klass. Spara alternativ för export till SVG-format i C++."
type: docs
weight: 15800
url: /sv/cpp/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class


Sparaalternativ för export till SVG-format.

```cpp
class PptxSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CustomProgressHandler](./get_customprogresshandler/)() const | Den här hanteraren kan användas för att hantera konverteringsförloppshändelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om aktuellt antal bearbetade sidor. Exempel på hanterarens kod som visar förloppet i konsolen är: |
| [get_ImageResolution](./get_imageresolution/)() const | Hämtar bildens upplösning (dpi). Standard är 192 dpi. |
| [get_OptimizeTextBoxes](./get_optimizetextboxes/)() const | Växlar igenkänning av textkolumner. |
| [get_SeparateImages](./get_separateimages/)() const | Om den är satt till true separeras bilder från all annan grafik. |
| [get_SlidesAsImages](./get_slidesasimages/)() const | Om den är satt till true känns allt innehåll igen som bilder (en per sida) |
| [PptxSaveOptions](./pptxsaveoptions/)() | Konstruktor. |
| [set_CustomProgressHandler](./set_customprogresshandler/)(UnifiedSaveOptions::ConversionProgressEventHandler) | Den här hanteraren kan användas för att hantera konverteringsförloppshändelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om aktuellt antal bearbetade sidor. Exempel på hanterarens kod som visar förloppet i konsolen är: |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Ställer in bildens upplösning (dpi). Standard är 192 dpi. |
| [set_OptimizeTextBoxes](./set_optimizetextboxes/)(bool) | Växlar igenkänning av textkolumner. |
| [set_SeparateImages](./set_separateimages/)(bool) | Om den är satt till true separeras bilder från all annan grafik. |
| [set_SlidesAsImages](./set_slidesasimages/)(bool) | Om den är satt till true känns allt innehåll igen som bilder (en per sida) |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
