---
title: "System::Drawing::Bitmap class"
linktitle: "Bitmap"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::Bitmap. Представляет изображение bitmap GDI+. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.drawing/bitmap/
---
## Bitmap class


Представляет изображение bitmap GDI+. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Bitmap : public System::Drawing::Image
```

## Методы

| Метод | Описание |
| --- | --- |
| [BeginPixelProcessing](./beginpixelprocessing/)(bool) | Включает режим обработки пикселей. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&) | Создаёт новый объект [Bitmap](./) из указанного существующего изображения. |
| [Bitmap](./bitmap/)(const SharedPtr\<System::IO::Stream\>\&, bool) | Создаёт новый объект [Bitmap](./) из указанного потока. |
| [Bitmap](./bitmap/)(const String\&) | Создаёт новый объект [Bitmap](./) из указанного файла. |
| [Bitmap](./bitmap/)(const String\&, bool) | Создаёт новый объект [Bitmap](./) из указанного файла. |
| [Bitmap](./bitmap/)(int, int, Imaging::PixelFormat) | Создаёт новый объект [Bitmap](./), представляющий bitmap‑изображение с указанными шириной, высотой, форматом пикселей и данными пикселей. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, const Size\&) | Создаёт новый объект [Bitmap](./) из указанного существующего изображения, масштабированного до указанного размера. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, int, int) | Создаёт новый объект [Bitmap](./) из указанного существующего изображения, ширина и высота которого масштабированы до указанных значений. |
| [Clone](./clone/)() override | Создаёт копию текущего объекта. |
| [Clone](./clone/)(Rectangle, Imaging::PixelFormat) | Создаёт объект [Bitmap](./), представляющий копию области bitmap‑изображения, представленного текущим объектом. |
| [Clone](./clone/)(RectangleF, Imaging::PixelFormat) | Создаёт объект [Bitmap](./), представляющий копию области bitmap‑изображения, представленного текущим объектом. |
| [ComputeHash](./computehash/)() | Вычисляет значение хеша SHA1. |
| static [ConvertToARGBImage](./converttoargbimage/)(const SharedPtr\<Bitmap\>\&) | Создаёт копию указанного bitmap‑изображения с изменённым форматом пикселей на Format32bppArgb. |
| [EndPixelProcessing](./endpixelprocessing/)(bool) | Отключает режим обработки пикселей. |
| [get_Height](./get_height/)() const override | Возвращает высоту изображения в пикселях. |
| [get_Palette](./get_palette/)() const override | Возвращает цветовую палитру, используемую изображением, представленным текущим объектом. |
| [get_PixelFormat](./get_pixelformat/)() const override | Возвращает формат пикселей изображения, представленного текущим объектом. |
| [get_RawFormat](./get_rawformat/)() const override | Возвращает формат файла изображения, представленного текущим объектом. |
| [get_Width](./get_width/)() const override | Возвращает ширину изображения в пикселях. |
| [GetHbitmap](./gethbitmap/)() | Создает объект GDI bitmap из bitmap, представленного текущим объектом. |
| [GetPixel](./getpixel/)(int, int) | Возвращает цвет указанного пикселя. |
| [GetSkBitmap](./getskbitmap/)() const override | Возвращает необработанный указатель на базовый объект SkBitmap. |
| [IsMultiImage](./ismultiimage/)() const override | Возвращает, является ли исходный формат многокадровым изображением. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) | Блокирует [Bitmap](./) в системной памяти. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) | Блокирует [Bitmap](./) в системной памяти. |
| [MakeTransparent](./maketransparent/)(Color) | Изменяет цвет всех пикселей указанного цвета на прозрачный. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(Bitmap, CODEPORTING_ARGS(const SharedPtr\<Image\>\&original, int width, int height), CODEPORTING_ARGS(original, width, height)) |  |
| [PremultipleColors](./premultiplecolors/)() | Предмультиплицирует цвета пикселей изображения, представленного текущим объектом. |
| [RotateFlip](./rotateflip/)(RotateFlipType) override | Поворачивает изображение на кратное 90 градусов и отражает. |
| [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) override | Устанавливает цветовую палитру, используемую изображением, представленным текущим объектом. |
| [SetPixel](./setpixel/)(int, int, Color) | Устанавливает цвет указанного пикселя в bitmap‑изображении, представленного текущим объектом. |
| [SetResolution](./setresolution/)(float, float) | Устанавливает разрешение изображения. |
| [UnlockBits](./unlockbits/)(const Imaging::BitmapDataPtr\&) | Разблокирует указанный bitmap из системной памяти. |
## См. также

* Class [Image](../image/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
