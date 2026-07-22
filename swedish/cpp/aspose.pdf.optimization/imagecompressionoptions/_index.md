---
title: "Aspose::Pdf::Optimization::ImageCompressionOptions class"
linktitle: "ImageCompressionOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Optimization::ImageCompressionOptions class. Klassen innehåller inställda alternativ för bildkomprimering i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class


Klassen innehåller en uppsättning alternativ för bildkomprimering.

```cpp
class ImageCompressionOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CompressImages](./get_compressimages/)() const | Om denna flagga är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
| [get_Encoding](./get_encoding/)() const | Hämtar kodning som används för att lagra bilder. |
| [get_ImageQuality](./get_imagequality/)() const | Anger nivån för bildkomprimering när flaggan CompressImages används. |
| [get_MaxResolution](./get_maxresolution/)() const | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [get_ResizeImages](./get_resizeimages/)() const | Om denna flagga är satt till true och CompressImages är true kommer bilder att ändras i storlek om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [get_Version](./get_version/)() const | Version av komprimeringsalgoritm. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kan vara otillämplig för vissa bilder), 3. mixed (standardkomprimering tillämpas på bilder som inte kan komprimeras av den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än "fast"‑algoritmen. Version "Fast" är inte tillämplig för storleksändring av bilder (standardmetoden kommer att användas). Standard är "Standard". |
| [ImageCompressionOptions](./imagecompressionoptions/)() |  |
| [set_CompressImages](./set_compressimages/)(bool) | Om denna flagga är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
| [set_Encoding](./set_encoding/)(ImageEncoding) | Ställer in kodning som används för att lagra bilder. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Anger nivån för bildkomprimering när flaggan CompressImages används. |
| [set_MaxResolution](./set_maxresolution/)(int32_t) | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [set_ResizeImages](./set_resizeimages/)(bool) | Om denna flagga är satt till true och CompressImages är true kommer bilder att ändras i storlek om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [set_Version](./set_version/)(ImageCompressionVersion) | Version av komprimeringsalgoritm. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kan vara otillämplig för vissa bilder), 3. mixed (standardkomprimering tillämpas på bilder som inte kan komprimeras av den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än "fast"‑algoritmen. Version "Fast" är inte tillämplig för storleksändring av bilder (standardmetoden kommer att användas). Standard är "Standard". |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
