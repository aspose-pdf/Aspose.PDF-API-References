---
title: "Aspose::Pdf::Image klass"
linktitle: "Image"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Image klass. Representerar bild i C++."
type: docs
weight: 7900
url: /sv/cpp/aspose.pdf/image/
---
## Image class


Representerar bild.

```cpp
class Image : public Aspose::Pdf::BaseParagraph
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klona bilden. |
| [get_BitmapInfo](./get_bitmapinfo/)() const | Hämtar okomprimerade bild-byte. |
| [get_BitmapSize](./get_bitmapsize/)() | Hämtar bildens bitmap-storlek. |
| [get_File](./get_file/)() const | Hämtar bildfilen. |
| [get_FileType](./get_filetype/)() const | Hämtar bildfilens typ. |
| [get_FixHeight](./get_fixheight/)() const | Hämtar bildens höjd. |
| [get_FixWidth](./get_fixwidth/)() const | Hämtar bildens bredd. |
| [get_ImageScale](./get_imagescale/)() const | Hämtar bildens skala. |
| [get_ImageStream](./get_imagestream/)() const | Hämtar bildströmmen. |
| [get_IsApplyResolution](./get_isapplyresolution/)() const | Hämtar ett booleskt värde som indikerar om bilden använder upplösning under generering. |
| [get_IsBlackWhite](./get_isblackwhite/)() const | Hämtar ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-underformat används måste denna egenskap sättas till true. |
| [get_Title](./get_title/)() const | Hämtar ett strängvärde som indikerar bildens titel. |
| static [GetMimeType](./getmimetype/)(const System::SharedPtr\<System::Drawing::Image\>\&) | Returnerar MIME-typ för bilden. |
| [Image](./image/)() |  |
| [set_BitmapInfo](./set_bitmapinfo/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) | Ställer in okomprimerade bildbytes. |
| [set_File](./set_file/)(const System::String\&) | Ställer in bildfilen. |
| [set_FileType](./set_filetype/)(ImageFileType) | Ställer in bildfilens typ. |
| [set_FixHeight](./set_fixheight/)(double) | Ställer in bildens höjd. |
| [set_FixWidth](./set_fixwidth/)(double) | Ställer in bildens bredd. |
| [set_ImageScale](./set_imagescale/)(double) | Ställer in bildens skala. |
| [set_ImageStream](./set_imagestream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in bildströmmen. |
| [set_IsApplyResolution](./set_isapplyresolution/)(bool) | Ställer in ett booleskt värde som indikerar om bilden använder upplösning under generering. |
| [set_IsBlackWhite](./set_isblackwhite/)(bool) | Ställer in ett booleskt värde som indikerar om bilden tvingas vara svartvit. Om en TIFF-bild av CCITT-underformat används måste denna egenskap sättas till true. |
| [set_Title](./set_title/)(const System::SharedPtr\<Text::TextFragment\>\&) | Ställer in ett strängvärde som indikerar bildens titel. |
## Se även

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
