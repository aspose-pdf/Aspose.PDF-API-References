---
title: "Aspose::Pdf::ImageStamp класс"
linktitle: "ImageStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::ImageStamp класс. Представляет графическую печать в C++."
type: docs
weight: 8300
url: /ru/cpp/aspose.pdf/imagestamp/
---
## ImageStamp class


Представляет графическую печать.

```cpp
class ImageStamp : public Aspose::Pdf::Stamp
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AlternativeText](./get_alternativetext/)() const | Получает альтернативный [Text](../../aspose.pdf.text/) для графической печати. |
| [get_Height](./get_height/)() override | Получает высоту изображения. Установка этого изображения позволяет масштабировать его по вертикали. |
| [get_Image](./get_image/)() const | Получает поток изображения, используемый для печати. |
| [get_Quality](./get_quality/)() const | Получает качество графической печати в процентах. Допустимые значения от 0 до 100%. |
| [get_Width](./get_width/)() override | Получает ширину изображения. Установка этого свойства позволяет масштабировать изображение по горизонтали. |
| [get_XIndent](./get_xindent/)() override | Получает и задает горизонтальную координату печати, начиная с левого края. |
| [get_YIndent](./get_yindent/)() override | Получает и задает вертикальную координату печати, начиная с нижнего края. |
| [ImageStamp](./imagestamp/)(const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый экземпляр класса [ImageStamp](./). |
| [ImageStamp](./imagestamp/)(const System::String\&) | Создаёт графическую печать из изображения в указанном файле. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Добавляет графическую печать на страницу. |
| [set_AlternativeText](./set_alternativetext/)(const System::String\&) | Устанавливает альтернативный [Text](../../aspose.pdf.text/) для графической печати. |
| [set_Height](./set_height/)(double) override | Устанавливает высоту изображения. Установка этого изображения позволяет масштабировать его по вертикали. |
| [set_Quality](./set_quality/)(int32_t) | Устанавливает качество графической печати в процентах. Допустимые значения от 0 до 100%. |
| [set_Width](./set_width/)(double) override | Устанавливает ширину изображения. Установка этого свойства позволяет масштабировать изображение по горизонтали. |
| [set_XIndent](./set_xindent/)(double) override | Получает и задает горизонтальную координату печати, начиная с левого края. |
| [set_YIndent](./set_yindent/)(double) override | Получает и задает вертикальную координату печати, начиная с нижнего края. |
## См. также

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
