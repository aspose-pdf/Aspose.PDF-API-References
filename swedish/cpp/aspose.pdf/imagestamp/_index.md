---
title: "Aspose::Pdf::ImageStamp klass"
linktitle: "ImageStamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ImageStamp klass. Representerar en grafisk stämpel i C++."
type: docs
weight: 8300
url: /sv/cpp/aspose.pdf/imagestamp/
---
## ImageStamp class


Representerar en grafisk stämpel.

```cpp
class ImageStamp : public Aspose::Pdf::Stamp
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AlternativeText](./get_alternativetext/)() const | Hämtar alternativ [Text](../../aspose.pdf.text/) för bildstämpel. |
| [get_Height](./get_height/)() override | Hämtar bildhöjd. Att ange den här bilden möjliggör vertikal skalning av bilden. |
| [get_Image](./get_image/)() const | Hämtar bildström som används för stämpling. |
| [get_Quality](./get_quality/)() const | Hämtar kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%. |
| [get_Width](./get_width/)() override | Hämtar bildbredd. Att ange den här egenskapen möjliggör horisontell skalning av bilden. |
| [get_XIndent](./get_xindent/)() override | Hämtar och anger horisontell stämpelkoordinat, räknat från vänster. |
| [get_YIndent](./get_yindent/)() override | Hämtar och anger vertikal stämpelkoordinat, räknat från botten. |
| [ImageStamp](./imagestamp/)(const System::SharedPtr\<System::IO::Stream\>\&) | Initierar en ny instans av klassen [ImageStamp](./). |
| [ImageStamp](./imagestamp/)(const System::String\&) | Skapar bildstämpel från bild i den angivna filen. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Lägger till grafisk stämpel på sidan. |
| [set_AlternativeText](./set_alternativetext/)(const System::String\&) | Anger alternativ [Text](../../aspose.pdf.text/) för bildstämpel. |
| [set_Height](./set_height/)(double) override | Anger bildhöjd. Att ange den här bilden möjliggör vertikal skalning av bilden. |
| [set_Quality](./set_quality/)(int32_t) | Anger kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%. |
| [set_Width](./set_width/)(double) override | Anger bildbredd. Att ange den här egenskapen möjliggör horisontell skalning av bilden. |
| [set_XIndent](./set_xindent/)(double) override | Hämtar och anger horisontell stämpelkoordinat, räknat från vänster. |
| [set_YIndent](./set_yindent/)(double) override | Hämtar och anger vertikal stämpelkoordinat, räknat från botten. |
## Se även

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
