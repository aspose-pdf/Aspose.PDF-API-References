---
title: "Aspose::Pdf::LowCode::TiffOptions-klass"
linktitle: "TiffOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::TiffOptions-klass. Representerar Pdf‑till‑Tiff‑konverteringsalternativ för Tiff‑plugin‑modulen i C++."
type: docs
weight: 8900
url: /sv/cpp/aspose.pdf.lowcode/tiffoptions/
---
## TiffOptions class


Representerar [Pdf](../../aspose.pdf/)‑till‑[Tiff](../tiff/)‑konverteringsalternativ för [Tiff](../tiff/)-plugin‑modulen.

```cpp
class TiffOptions : public Aspose::Pdf::LowCode::PdfToImageOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Brightness](./get_brightness/)() | Hämtar eller anger ett värdegräns för färgtransformeringen mellan vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1. |
| [get_Compression](./get_compression/)() | Hämtar kompressionstypen. |
| [get_CoordinateType](./get_coordinatetype/)() | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [get_Depth](./get_depth/)() | Hämtar färgdjupet. |
| [get_OperationName](./get_operationname/)() override | Returnerar namn på operationen. |
| [get_SaveAsMultiPageTiff](./get_saveasmultipagetiff/)() const | Hämtar och sätter flagga som tillåter att spara alla sidor i en flersidig TIFF. |
| [get_Shape](./get_shape/)() | Hämtar typ av formen. |
| [get_SkipBlankPages](./get_skipblankpages/)() | Hämtar ett värde som indikerar om tomma sidor ska hoppas över. |
| [set_Brightness](./set_brightness/)(float) | Hämtar eller anger ett värdegräns för färgtransformeringen mellan vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1. |
| [set_Compression](./set_compression/)(Devices::CompressionType) | Sätter komprimeringstypen. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [set_Depth](./set_depth/)(Devices::ColorDepth) | Sätter färgdjupet. |
| [set_SaveAsMultiPageTiff](./set_saveasmultipagetiff/)(bool) | Hämtar och sätter flagga som tillåter att spara alla sidor i en flersidig TIFF. |
| [set_Shape](./set_shape/)(Devices::ShapeType) | Sätter typ av formen. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Sätter ett värde som indikerar om tomma sidor ska hoppas över. |
| [TiffOptions](./tiffoptions/)() | Initierar en ny instans av objektet [TiffOptions](./). |
## Se även

* Class [PdfToImageOptions](../pdftoimageoptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
