---
title: "System::Drawing::Image klass"
linktitle: "Image"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Image klass. En basklass för System::Drawing::Bitmap och System::Drawing::Metafile-klasser som tillhandahåller grundläggande funktionalitet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.drawing/image/
---
## Image class


En basklass för [System::Drawing::Bitmap](../bitmap/) och System::Drawing::Metafile-klasser som tillhandahåller grundläggande funktionalitet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Image : public virtual System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Clone](./clone/)() | Skapar en kopia av det aktuella objektet. |
| [Dispose](./dispose/)() override | Frigör alla resurser som erhållits av det aktuella objektet. |
| static [FromFile](./fromfile/)(const String\&, bool) | Skapar ett [Image](./)-objekt från den angivna filen. |
| static [FromHbitmap](./fromhbitmap/)(IntPtr) | Skapar ett [Bitmap](../bitmap/)-objekt från den angivna GDI-bitmapen. |
| static [FromStream](./fromstream/)(const SharedPtr\<System::IO::Stream\>\&, bool, bool) | Skapar ett [Image](./)-objekt från den angivna strömmen. |
| virtual [get_Flags](./get_flags/)() const | Returnerar en bitvis kombination av ImageFlags-enumvärden som representerar bildens attribut. |
| [get_FrameDimensionsList](./get_framedimensionslist/)() const | Returnerar en array av GUID‑värden som representerar dimensionerna för ramar inom bilden som representeras av det aktuella objektet. |
| virtual [get_Height](./get_height/)() const | Returnerar bildens höjd i pixlar. |
| [get_HorizontalResolution](./get_horizontalresolution/)() const | Returnerar den horisontella upplösningen för bilden som representeras av det aktuella objektet i pixlar per tum. |
| virtual [get_Palette](./get_palette/)() const | Returnerar färgpaletten som används av bilden som representeras av det aktuella objektet. |
| virtual [get_PixelFormat](./get_pixelformat/)() const | Returnerar pixelformatet för bilden som representeras av det aktuella objektet. |
| virtual [get_PropertyIdList](./get_propertyidlist/)() const | Hämtar ID:n för egenskapsobjekten som lagras i denna bild. |
| virtual [get_PropertyItems](./get_propertyitems/)() const | Hämtar alla egenskapsobjekt (metadata) som lagras i denna bild. |
| virtual [get_RawFormat](./get_rawformat/)() const | Returnerar filformatet för bilden som representeras av det aktuella objektet. |
| [get_Size](./get_size/)() const | Returnerar ett [Size](../size/)-objekt som representerar bildens bredd och höjd i pixlar. |
| virtual [get_Tag](./get_tag/)() const | Hämtar ett objekt som tillhandahåller ytterligare data om bilden. |
| [get_VerticalResolution](./get_verticalresolution/)() const | Returnerar den vertikala upplösningen för bilden som representeras av det aktuella objektet i pixlar per tum. |
| virtual [get_Width](./get_width/)() const | Returnerar bildens bredd i pixlar. |
| [GetBounds](./getbounds/)(GraphicsUnit\&) | Returnerar bildens gränser i de angivna mätenheterna. |
| [GetFrameCount](./getframecount/)(const Imaging::FrameDimensionPtr\&) | Returnerar antalet ramar för den angivna ramdimensionen. |
| static [GetPixelFormatSize](./getpixelformatsize/)(Imaging::PixelFormat) | Returnerar antalet bitar som används för att representera färgdjupet i det angivna pixelformatet. |
| virtual [GetSkBitmap](./getskbitmap/)() const | Returnerar ett underliggande SkBitmap-objekt. |
| [GetThumbnailImage](./getthumbnailimage/)(int, int, Image::GetThumbnailImageAbort, IntPtr) | Hämtar en miniatyr för detta [System::Drawing::Image](./)-objekt. |
| static [IsAlphaPixelFormat](./isalphapixelformat/)(Imaging::PixelFormat) | Avgör om det angivna pixelformatet innehåller alfainformation. |
| virtual [IsMultiImage](./ismultiimage/)() const | Returnerar om det ursprungliga formatet är en multi-bild. |
| virtual [RotateFlip](./rotateflip/)(RotateFlipType) | Rotera bilden till en multipel av 90 grader och vänd. |
| [Save](./save/)(const String\&) | Sparar bilden som representeras av det aktuella objektet till den angivna filen i PNG-format. |
| [Save](./save/)(const String\&, const Imaging::ImageFormatPtr\&) | Sparar bilden som representeras av det aktuella objektet till den angivna filen i det angivna formatet. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) | Sparar bilden som representeras av det aktuella objektet till den angivna strömmen i det angivna formatet. |
| [Save](./save/)(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Sparar bilden som representeras av det aktuella objektet till den angivna filen med den angivna kodaren och kodarparametrarna. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Sparar bilden som representeras av det aktuella objektet till den angivna strömmen med den angivna kodaren och kodarparametrarna. |
| [SaveAdd](./saveadd/)(const Imaging::EncoderParametersPtr\&) | Lägger till en ram i den fil eller ström som angavs i ett tidigare anrop till metoden [Save()](./save/). |
| [SaveAdd](./saveadd/)(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) | Lägger till en ram i den fil eller ström som angavs i ett tidigare anrop till metoden [Save()](./save/). |
| [SelectActiveFrame](./selectactiveframe/)(const Imaging::FrameDimensionPtr\&, int) | Väljer den angivna ramen. |
| virtual [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) | Ställer in färgpaletten som används av bilden som representeras av det aktuella objektet. |
| virtual [set_Tag](./set_tag/)(const System::SharedPtr\<System::Object\>) | Ställer in ett objekt som tillhandahåller ytterligare data om bilden. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | Ett återanrop för att avbryta GetThumbnailImage-exekveringen. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
