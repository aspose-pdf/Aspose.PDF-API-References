---
title: "System::Drawing::Bitmap class"
linktitle: "Bitmap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Bitmap-klass. Representerar en GDI+ bitmap-bild. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.drawing/bitmap/
---
## Bitmap class


Representerar en GDI+ bitmap-bild. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Bitmap : public System::Drawing::Image
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BeginPixelProcessing](./beginpixelprocessing/)(bool) | Aktiverar pixelbehandlingsläge. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&) | Skapar ett nytt [Bitmap](./)-objekt från den angivna befintliga bilden. |
| [Bitmap](./bitmap/)(const SharedPtr\<System::IO::Stream\>\&, bool) | Skapar ett nytt [Bitmap](./)-objekt från den angivna strömmen. |
| [Bitmap](./bitmap/)(const String\&) | Skapar ett nytt [Bitmap](./)-objekt från den angivna filen. |
| [Bitmap](./bitmap/)(const String\&, bool) | Skapar ett nytt [Bitmap](./)-objekt från den angivna filen. |
| [Bitmap](./bitmap/)(int, int, Imaging::PixelFormat) | Skapar ett nytt [Bitmap](./)-objekt som representerar en bitmap-bild med den angivna bredden, höjden, pixelformatet och pixeldata. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, const Size\&) | Skapar ett nytt [Bitmap](./)-objekt från den angivna befintliga bilden, skalad till den angivna storleken. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, int, int) | Skapar ett nytt [Bitmap](./)-objekt från den angivna befintliga bilden med bredd och höjd skalade till de angivna värdena. |
| [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| [Clone](./clone/)(Rectangle, Imaging::PixelFormat) | Skapar ett [Bitmap](./)-objekt som representerar en kopia av en region i bitmap-bilden som representeras av det aktuella objektet. |
| [Clone](./clone/)(RectangleF, Imaging::PixelFormat) | Skapar ett [Bitmap](./)-objekt som representerar en kopia av en region i bitmap-bilden som representeras av det aktuella objektet. |
| [ComputeHash](./computehash/)() | Beräknar SHA1-hashvärdet. |
| static [ConvertToARGBImage](./converttoargbimage/)(const SharedPtr\<Bitmap\>\&) | Skapar en kopia av den angivna bitmap-bilden med pixelformat ändrat till Format32bppArgb. |
| [EndPixelProcessing](./endpixelprocessing/)(bool) | Inaktiverar pixelbehandlingsläge. |
| [get_Height](./get_height/)() const override | Returnerar bildens höjd i pixlar. |
| [get_Palette](./get_palette/)() const override | Returnerar färgpaletten som används av bilden som representeras av det aktuella objektet. |
| [get_PixelFormat](./get_pixelformat/)() const override | Returnerar pixelformatet för bilden som representeras av det aktuella objektet. |
| [get_RawFormat](./get_rawformat/)() const override | Returnerar filformatet för bilden som representeras av det aktuella objektet. |
| [get_Width](./get_width/)() const override | Returnerar bildens bredd i pixlar. |
| [GetHbitmap](./gethbitmap/)() | Skapar ett GDI-bitmap-objekt från bitmapen som representeras av det aktuella objektet. |
| [GetPixel](./getpixel/)(int, int) | Returnerar färgen på den angivna pixeln. |
| [GetSkBitmap](./getskbitmap/)() const override | Returnerar en rå pekare till det underliggande SkBitmap-objektet. |
| [IsMultiImage](./ismultiimage/)() const override | Returnerar om det ursprungliga formatet är en multi-bild. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) | Låser en [Bitmap](./) i systemminnet. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) | Låser en [Bitmap](./) i systemminnet. |
| [MakeTransparent](./maketransparent/)(Color) | Ändrar färgen på alla pixlar med den angivna färgen till transparent. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(Bitmap, CODEPORTING_ARGS(const SharedPtr\<Image\>\&original, int width, int height), CODEPORTING_ARGS(original, width, height)) |  |
| [PremultipleColors](./premultiplecolors/)() | Förmultiplicerar färgerna på pixelna i bilden som representeras av det aktuella objektet. |
| [RotateFlip](./rotateflip/)(RotateFlipType) override | Rotera bilden till en multipel av 90 grader och vänd. |
| [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) override | Ställer in färgpaletten som används av bilden som representeras av det aktuella objektet. |
| [SetPixel](./setpixel/)(int, int, Color) | Ställer in färgen på den angivna pixeln i bitmap-bilden som representeras av det aktuella objektet. |
| [SetResolution](./setresolution/)(float, float) | Ställer in bildens upplösning. |
| [UnlockBits](./unlockbits/)(const Imaging::BitmapDataPtr\&) | Låser upp den angivna bitmapen från systemminnet. |
## Se även

* Class [Image](../image/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
