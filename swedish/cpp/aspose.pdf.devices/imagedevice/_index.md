---
title: "Aspose::Pdf::Devices::ImageDevice klass"
linktitle: "ImageDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::ImageDevice klass. En abstrakt klass för bildenheter i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.devices/imagedevice/
---
## ImageDevice class


En abstrakt klass för bildenheter.

```cpp
class ImageDevice : public Aspose::Pdf::Devices::PageDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CoordinateType](./get_coordinatetype/)() const | Hämtar sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Hämtar formulär presentationsläge. |
| [get_Height](./get_height/)() const | Hämtar bildens utdatahöjd. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Hämtar renderingsalternativ. |
| [get_Resolution](./get_resolution/)() const | Hämtar bildens upplösning. |
| [get_Width](./get_width/)() const | Hämtar bildens utdata­bredd. |
| [GetBitmap](./getbitmap/)(const System::SharedPtr\<Page\>\&) | Konverterar sidan till [Bitmap](../). |
| [ImageDevice](./imagedevice/)() | Abstrakt initierare för [ImageDevice](./)-avstammade, sätt upplösning till 150x150. |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Abstrakt initierare för [ImageDevice](./)-avstammade. |
| [ImageDevice](./imagedevice/)(int32_t, int32_t) | Initierar en ny instans av [JpegDevice](../jpegdevice/) klass med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av [JpegDevice](../jpegdevice/) klass med angivna bilddimensioner och standardupplösning (=150). |
| [ImageDevice](./imagedevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av [JpegDevice](../jpegdevice/) klass med angivna bilddimensioner och upplösning. |
| [ImageDevice](./imagedevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av [JpegDevice](../jpegdevice/) klass med angivna bilddimensioner och upplösning. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Ställer in formulärets presentationsläge. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Ställer in renderingsalternativ. |
## Se även

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
