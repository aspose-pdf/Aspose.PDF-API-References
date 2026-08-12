---
title: "System::Drawing::Image класс"
linktitle: "Image"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Image class. Базовый класс для классов System::Drawing::Bitmap и System::Drawing::Metafile, предоставляющий базовую функциональность. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.drawing/image/
---
## Image class


Базовый класс для [System::Drawing::Bitmap](../bitmap/) и классов System::Drawing::Metafile, предоставляющий базовую функциональность. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Image : public virtual System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Clone](./clone/)() | Создаёт копию текущего объекта. |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, полученные текущим объектом. |
| static [FromFile](./fromfile/)(const String\&, bool) | Создает объект [Image](./) из указанного файла. |
| static [FromHbitmap](./fromhbitmap/)(IntPtr) | Создает объект [Bitmap](../bitmap/) из указанного GDI‑битмапа. |
| static [FromStream](./fromstream/)(const SharedPtr\<System::IO::Stream\>\&, bool, bool) | Создает объект [Image](./) из указанного потока. |
| virtual [get_Flags](./get_flags/)() const | Возвращает побитовую комбинацию значений перечисления ImageFlags, представляющих атрибуты изображения. |
| [get_FrameDimensionsList](./get_framedimensionslist/)() const | Возвращает массив GUID, представляющих размеры кадров в изображении, представленном текущим объектом. |
| virtual [get_Height](./get_height/)() const | Возвращает высоту изображения в пикселях. |
| [get_HorizontalResolution](./get_horizontalresolution/)() const | Возвращает горизонтальное разрешение изображения, представленного текущим объектом, в пикселях на дюйм. |
| virtual [get_Palette](./get_palette/)() const | Возвращает цветовую палитру, используемую изображением, представленным текущим объектом. |
| virtual [get_PixelFormat](./get_pixelformat/)() const | Возвращает формат пикселей изображения, представленного текущим объектом. |
| virtual [get_PropertyIdList](./get_propertyidlist/)() const | Получает идентификаторы элементов свойств, хранящихся в этом изображении. |
| virtual [get_PropertyItems](./get_propertyitems/)() const | Получает все элементы свойств (части метаданных), хранящиеся в этом изображении. |
| virtual [get_RawFormat](./get_rawformat/)() const | Возвращает формат файла изображения, представленного текущим объектом. |
| [get_Size](./get_size/)() const | Возвращает объект [Size](../size/), представляющий ширину и высоту изображения в пикселях. |
| virtual [get_Tag](./get_tag/)() const | Получает объект, предоставляющий дополнительные данные об изображении. |
| [get_VerticalResolution](./get_verticalresolution/)() const | Возвращает вертикальное разрешение изображения, представленного текущим объектом, в пикселях на дюйм. |
| virtual [get_Width](./get_width/)() const | Возвращает ширину изображения в пикселях. |
| [GetBounds](./getbounds/)(GraphicsUnit\&) | Возвращает границы изображения в указанных единицах измерения. |
| [GetFrameCount](./getframecount/)(const Imaging::FrameDimensionPtr\&) | Возвращает количество кадров указанного измерения кадра. |
| static [GetPixelFormatSize](./getpixelformatsize/)(Imaging::PixelFormat) | Возвращает количество бит, используемых для представления глубины цвета в указанном формате пикселей. |
| virtual [GetSkBitmap](./getskbitmap/)() const | Возвращает базовый объект SkBitmap. |
| [GetThumbnailImage](./getthumbnailimage/)(int, int, Image::GetThumbnailImageAbort, IntPtr) | Получает миниатюру для этого объекта [System::Drawing::Image](./). |
| static [IsAlphaPixelFormat](./isalphapixelformat/)(Imaging::PixelFormat) | Определяет, содержит ли указанный формат пикселей альфа‑информацию. |
| virtual [IsMultiImage](./ismultiimage/)() const | Возвращает, является ли исходный формат многокадровым изображением. |
| virtual [RotateFlip](./rotateflip/)(RotateFlipType) | Поворачивает изображение на кратное 90 градусов и отражает его. |
| [Save](./save/)(const String\&) | Сохраняет изображение, представленное текущим объектом, в указанный файл в формате PNG. |
| [Save](./save/)(const String\&, const Imaging::ImageFormatPtr\&) | Сохраняет изображение, представленное текущим объектом, в указанный файл в указанном формате. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) | Сохраняет изображение, представленное текущим объектом, в указанный поток в указанном формате. |
| [Save](./save/)(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Сохраняет изображение, представленное текущим объектом, в указанный файл, используя указанный кодировщик и параметры кодировщика. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Сохраняет изображение, представленное текущим объектом, в указанный поток, используя указанный кодировщик и параметры кодировщика. |
| [SaveAdd](./saveadd/)(const Imaging::EncoderParametersPtr\&) | Добавляет кадр в файл или поток, указанные в предыдущем вызове метода [Save()](./save/) метод. |
| [SaveAdd](./saveadd/)(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) | Добавляет кадр в файл или поток, указанные в предыдущем вызове метода [Save()](./save/) метод. |
| [SelectActiveFrame](./selectactiveframe/)(const Imaging::FrameDimensionPtr\&, int) | Выбирает указанный кадр. |
| virtual [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) | Устанавливает цветовую палитру, используемую изображением, представленным текущим объектом. |
| virtual [set_Tag](./set_tag/)(const System::SharedPtr\<System::Object\>) | Устанавливает объект, предоставляющий дополнительные данные об изображении. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | Обратный вызов для отмены выполнения GetThumbnailImage. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
