---
title: "Aspose::Pdf::Devices::TiffDevice class"
linktitle: "TiffDevice"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Devices::TiffDevice class. Denna klass hjälper till att spara PDF-dokument sida för sida i en tiff-bild i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class


Denna klass hjälper till att spara pdf-dokumentets sidor sida för sida i en enda tiff-bild.

```cpp
class TiffDevice : public Aspose::Pdf::Devices::DocumentDevice
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BinarizeBradley](./binarizebradley/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, double) | Utför Bradley-binarisering för inmatningsström. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Hämtar formulär presentationsläge. |
| [get_Height](./get_height/)() const | Hämtar bildens utdatahöjd. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Hämtar renderingsalternativ. |
| [get_Resolution](./get_resolution/)() const | Hämtar bildens upplösning. |
| [get_Settings](./get_settings/)() const | Hämtar inställningar för att mappa PDF till tiff‑bild. |
| [get_Width](./get_width/)() const | Hämtar bildens utdata­bredd. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) override | Konverterar vissa dokumentsidor till tiff och sparar dem i utdataströmmen. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Utför någon operation på den givna sidan, t.ex. konverterar sidan till en grafisk bild. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Ställer in formulärets presentationsläge. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Ställer in renderingsalternativ. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<TiffSettings\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)() | Initierar en ny instans av klassen [TiffDevice](./) med standardinställningar. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<TiffSettings\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<TiffSettings\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t) | Initierar en ny instans av klassen [TiffDevice](./) class. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&) | Initierar en ny instans av klassen [TiffDevice](./) class. |
## Se även

* Class [DocumentDevice](../documentdevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
