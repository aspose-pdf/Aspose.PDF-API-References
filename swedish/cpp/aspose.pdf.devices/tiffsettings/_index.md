---
title: "Aspose::Pdf::Devices::TiffSettings-klass"
linktitle: "TiffSettings"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::TiffSettings-klass. Denna klass representerar inställningar för att importera pdf till Tiff i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf.devices/tiffsettings/
---
## TiffSettings class


Denna klass representerar inställningar för import av pdf till Tiff.

```cpp
class TiffSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Brightness](./get_brightness/)() const | Hämtar eller anger ett värdegräns för färgtransformeringen mellan vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [get_Compression](./get_compression/)() const | Hämtar kompressionstypen. |
| [get_CoordinateType](./get_coordinatetype/)() const | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [get_Depth](./get_depth/)() const | Hämtar färgdjupet. |
| [get_Margins](./get_margins/)() const | Hämtar marginalerna. |
| [get_Shape](./get_shape/)() const | Hämtar typ av formen. |
| [get_SkipBlankPages](./get_skipblankpages/)() const | Hämtar ett värde som indikerar om tomma sidor ska hoppas över. |
| [set_Brightness](./set_brightness/)(float) | Hämtar eller anger ett värdegräns för färgtransformeringen mellan vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller [ColorDepth.Format1bpp](../colordepth/) == 1. |
| [set_Compression](./set_compression/)(CompressionType) | Sätter komprimeringstypen. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [set_Depth](./set_depth/)(ColorDepth) | Sätter färgdjupet. |
| [set_Shape](./set_shape/)(ShapeType) | Sätter typ av formen. |
| [set_SkipBlankPages](./set_skipblankpages/)(bool) | Sätter ett värde som indikerar om tomma sidor ska hoppas över. |
| [TiffSettings](./tiffsettings/)() | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(ShapeType) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(ColorDepth) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&, bool) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(CompressionType, ColorDepth, const System::SharedPtr\<Aspose::Pdf::Devices::Margins\>\&, bool, ShapeType) | Initierar en ny instans av klassen [TiffSettings](./). |
| [TiffSettings](./tiffsettings/)(bool) | Initierar en ny instans av klassen [TiffSettings](./). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
