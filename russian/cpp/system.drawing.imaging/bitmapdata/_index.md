---
title: "System::Drawing::Imaging::BitmapData class"
linktitle: "BitmapData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::BitmapData class. Представляет набор атрибутов растрового изображения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.drawing.imaging/bitmapdata/
---
## BitmapData class


Представляет набор атрибутов растрового изображения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class BitmapData : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Height](./get_height/)() const | Возвращает высоту изображения в пикселях. |
| [get_PixelFormat](./get_pixelformat/)() const | Возвращает формат пикселей растрового изображения. |
| [get_Scan0](./get_scan0/)() const | Возвращает адрес первых данных пикселя в растровом изображении. |
| [get_Stride](./get_stride/)() const | Возвращает ширину строки изображения в байтах. |
| [get_Width](./get_width/)() const | Возвращает ширину изображения в пикселях. |
| [set_Height](./set_height/)(int) | Устанавливает высоту изображения в пикселях. |
| [set_PixelFormat](./set_pixelformat/)(PixelFormat) | Устанавливает формат пикселей растрового изображения. |
| [set_Scan0](./set_scan0/)(IntPtr) | Устанавливает адрес первых данных пикселя в растровом изображении. |
| [set_Stride](./set_stride/)(int) | Устанавливает ширину шага изображения в байтах. |
| [set_Width](./set_width/)(int) | Устанавливает ширину изображения в пикселях. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
