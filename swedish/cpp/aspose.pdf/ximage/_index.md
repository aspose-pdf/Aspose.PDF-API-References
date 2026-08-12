---
title: "Aspose::Pdf::XImage klass"
linktitle: "XImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XImage klass. Klass som representerar bild X-Object i C++."
type: docs
weight: 19700
url: /sv/cpp/aspose.pdf/ximage/
---
## XImage class


Klass som representerar bild‑X‑Objekt.

```cpp
class XImage : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddStencilMask](./addstencilmask/)(const System::SharedPtr\<System::IO::Stream\>\&) | Lägger till en stencilmask till [XImage](./). |
| static [DetectColorType](./detectcolortype/)(const System::SharedPtr\<System::Drawing::Bitmap\>\&) | Returnerar färgtyp för bilden. |
| [get_ContainsTransparency](./get_containstransparency/)() | Om bilden innehåller transparens returneras true; annars false. |
| [get_FilterType](./get_filtertype/)() | Hämtar bildfiltertyp. |
| [get_Grayscaled](./get_grayscaled/)() | Hämtar gråskalig version av bilden. |
| [get_Height](./get_height/)() | Hämtar bildens höjd. |
| [get_ImageMask](./get_imagemask/)() | Hämtar en flagga som indikerar om bilden ska behandlas som en bildmask (se 8.9.6, "Masked Images"). Om denna flagga är sann ska värdet för BitsPerComponent vara 1 och Mask och [ColorSpace](../colorspace/) får inte anges; omaskerade områden ska målas med den aktuella icke‑strokande färgen. Standardvärde: false. |
| [get_Metadata](./get_metadata/)() | [Metadata](../metadata/) för bilden. |
| [get_Name](./get_name/)() | Hämtar bildens namn. Observera att om du ändrar namn på bilden som har referenser i sidinnehållet kan dokumentet bli felaktigt. Använd i så fall metoden [XImage.Rename](./rename/). |
| [get_Width](./get_width/)() | Hämtar bildens bredd. |
| [GetAlternativeText](./getalternativetext/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Returnerar en lista med strängar med alternativ [Text](../../aspose.pdf.text/) för en [XImage](./). |
| [GetColorType](./getcolortype/)() | Returnerar färgtyp för bilden. |
| [GetNameInCollection](./getnameincollection/)() | Returnerar bildens namn i dess samling. |
| [GetRawImageData](./getrawimagedata/)() | Hämtar den råa bilddatan från källbilden. |
| [IsTheSameObject](./isthesameobject/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Returnerar true om båda bilderna refererar till samma objekt. |
| [Rename](./rename/)(const System::String\&) | Byter namn på bilden och ersätter alla referenser till bilden med det nya namnet. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sparar bilddata till ström som JPEG-bild. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Sparar bilden till ström i önskat format. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Sparar bilddata till ström som JPEG-bild med angiven upplösning. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Sparar bilden till ström i önskat format med angiven upplösning. |
| [set_Name](./set_name/)(const System::String\&) | Sätter bildens namn. Observera att om du ändrar namn på bilden som har referenser i sidinnehållet kan dokumentet bli felaktigt. Använd i så fall metoden [XImage.Rename](./rename/). |
| [ToStream](./tostream/)() | Returnerar den ursprungliga bildströmmen. |
| [TrySetAlternativeText](./trysetalternativetext/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Sätter alternativ text för en [XImage](./) på sidan. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
