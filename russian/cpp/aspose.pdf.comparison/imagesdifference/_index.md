---
title: "Класс Aspose::Pdf::Comparison::ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Comparison::ImagesDifference. Представляет класс результата сравнения двух страниц PDF в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class


Представляет класс результата сравнения двух страниц PDF.

```cpp
class ImagesDifference : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [DifferenceToImage](./differencetoimage/)(const System::SharedPtr\<Color\>\&, const System::SharedPtr\<Color\>\&) | Преобразует массив различий в растровое изображение, используя указанные цвета. |
| [Dispose](./dispose/)() override | Выполняет все необходимые операции очистки перед уничтожением объекта. |
| [get_Difference](./get_difference/)() const | Получает массив различий. Этот массив похож на массив исходных данных изображения, полученный в результате метода LockBits. |
| [get_Height](./get_height/)() const | Высота различия. |
| [get_SourceImage](./get_sourceimage/)() const | Получает изображение первой сравниваемой страницы. Формат пикселей изображения — 24 bpp. |
| [get_Stride](./get_stride/)() const | Шаг (stride) данных изображения различий. |
| [GetDestinationImage](./getdestinationimage/)() | Возвращает новый растровый образ, представляющий целевое изображение, полученный применением массива различий к исходному изображению. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
