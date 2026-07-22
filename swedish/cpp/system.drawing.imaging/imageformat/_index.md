---
title: "System::Drawing::Imaging::ImageFormat class"
linktitle: "ImageFormat"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::ImageFormat class. Representerar filformatet för en bild. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.drawing.imaging/imageformat/
---
## ImageFormat class


Representerar filformatet för en bild. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ImageFormat : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(ImageFormatPtr) const | Bestämmer om bildformaten som representeras av det aktuella och det angivna objektet är lika. |
| static [get_Bmp](./get_bmp/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar bitmap-bildformatet. |
| static [get_Emf](./get_emf/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar det förbättrade metafilformatet. |
| static [get_Exif](./get_exif/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar Exchangeable [Image](../../system.drawing/image/) File (Exif)-formatet. |
| static [get_Gif](./get_gif/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar [Graphics](../../system.drawing/graphics/) Interchange Format (GIF)-bildformatet. |
| [get_Guid](./get_guid/)() const | Returnerar GUID:n som är associerad med bildformatet som representeras av det aktuella objektet. |
| static [get_Icon](./get_icon/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar [Windows](../../system.windows/) ikon-bildformatet. |
| static [get_Jpeg](./get_jpeg/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar Joint Photographic Experts Group (JPEG)-bildformatet. |
| static [get_MemoryBmp](./get_memorybmp/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar formatet för en bitmap i minnet. |
| static [get_Png](./get_png/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG)-bildformatet. |
| static [get_Tiff](./get_tiff/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar Tagged [Image](../../system.drawing/image/) File Format (TIFF)-bildformatet. |
| static [get_Wmf](./get_wmf/)() | Returnerar en delad pekare till ett [ImageFormat](./)-objekt som representerar [Windows](../../system.windows/) metafil (WMF)-bildformatet. |
| [ImageFormat](./imageformat/)(const System::Guid\&) | Skapar en instans av klassen [ImageFormat](./) som representerar ett bildformat kopplat till den angivna GUID:n. |
| virtual [ToString](./tostring/)() const | Konverterar detta [ImageFormat](./)-objekt till en människoläsbar sträng. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
