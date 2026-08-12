---
title: "Aspose::Pdf::XpsSaveOptions klass"
linktitle: "XpsSaveOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XpsSaveOptions klass. Spara alternativ för export till Xps-format i C++."
type: docs
weight: 21100
url: /sv/cpp/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class


Spara alternativ för export till Xps-format.

```cpp
class XpsSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BatchSize](./get_batchsize/)() override | Definierar batch‑storlek om batch‑konvertering är tillämplig för käll‑ och destinationsformatparet. |
| [get_DefaultFont](./get_defaultfont/)() const | Hämtar/anger standardteckensnittets namn. Används om det inbäddade teckensnittets namn inte hittas i systemet. |
| [get_SaveTransparentTexts](./get_savetransparenttexts/)() const | Anger om transparent (OCR:ad) text ska bevaras. |
| [get_UseEmbeddedTrueTypeFonts](./get_useembeddedtruetypefonts/)() const | Hämtar/anger flaggan för att använda inbäddade TrueType-teckensnitt. Att undvika användning av inbäddade TrueType-teckensnitt kan minska konverteringstiden. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Hämtar UseNewImagingEngine-alternativet. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Definierar batch‑storlek om batch‑konvertering är tillämplig för käll‑ och destinationsformatparet. |
| [set_DefaultFont](./set_defaultfont/)(const System::String\&) | Hämtar/anger standardteckensnittets namn. Används om det inbäddade teckensnittets namn inte hittas i systemet. |
| [set_SaveTransparentTexts](./set_savetransparenttexts/)(bool) | Anger om transparent (OCR:ad) text ska bevaras. |
| [set_UseEmbeddedTrueTypeFonts](./set_useembeddedtruetypefonts/)(bool) | Hämtar/anger flaggan för att använda inbäddade TrueType-teckensnitt. Att undvika användning av inbäddade TrueType-teckensnitt kan minska konverteringstiden. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Anger UseNewImagingEngine-alternativet. |
| [XpsSaveOptions](./xpssaveoptions/)() | Konstruktor. |
## Se även

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
