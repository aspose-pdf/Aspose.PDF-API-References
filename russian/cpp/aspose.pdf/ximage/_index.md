---
title: "Класс Aspose::Pdf::XImage"
linktitle: "XImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::XImage. Класс, представляющий X-Object изображения в C++."
type: docs
weight: 19700
url: /ru/cpp/aspose.pdf/ximage/
---
## XImage class


Класс, представляющий X-Object изображения.

```cpp
class XImage : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddStencilMask](./addstencilmask/)(const System::SharedPtr\<System::IO::Stream\>\&) | Добавляет трафаретную маску к [XImage](./). |
| static [DetectColorType](./detectcolortype/)(const System::SharedPtr\<System::Drawing::Bitmap\>\&) | Возвращает тип цвета изображения. |
| [get_ContainsTransparency](./get_containstransparency/)() | Если изображение содержит прозрачность, возвращает true; иначе — false. |
| [get_FilterType](./get_filtertype/)() | Получает тип фильтра изображения. |
| [get_Grayscaled](./get_grayscaled/)() | Получает градацию серого изображения. |
| [get_Height](./get_height/)() | Получает высоту изображения. |
| [get_ImageMask](./get_imagemask/)() | Получает флаг, указывающий, следует ли рассматривать изображение как маску изображения (см. 8.9.6, "Masked Images"). Если этот флаг установлен в true, значение BitsPerComponent должно быть 1, а Mask и [ColorSpace](../colorspace/) не должны указываться; немаскированные области должны быть закрашены текущим цветом без обводки. Значение по умолчанию: false. |
| [get_Metadata](./get_metadata/)() | [Metadata](../metadata/) изображения. |
| [get_Name](./get_name/)() | Получает имя изображения. Обратите внимание, что если вы измените имя изображения, которое имеет ссылки в содержимом страниц, документ может стать некорректным. В этом случае используйте метод [XImage.Rename](./rename/). |
| [get_Width](./get_width/)() | Получает ширину изображения. |
| [GetAlternativeText](./getalternativetext/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Возвращает список строк с альтернативным [Text](../../aspose.pdf.text/) для [XImage](./). |
| [GetColorType](./getcolortype/)() | Возвращает тип цвета изображения. |
| [GetNameInCollection](./getnameincollection/)() | Возвращает имя изображения в его коллекции. |
| [GetRawImageData](./getrawimagedata/)() | Извлекает необработанные данные изображения из исходного изображения. |
| [IsTheSameObject](./isthesameobject/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Возвращает true, если оба изображения ссылаются на один и тот же объект. |
| [Rename](./rename/)(const System::String\&) | Переименовывает изображение и заменяет все ссылки на изображение новым именем. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет данные изображения в поток в виде JPEG‑изображения. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сохраняет изображение в поток в запрошенном формате. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Сохраняет данные изображения в поток в виде JPEG‑изображения с указанным разрешением. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Сохраняет изображение в поток в запрошенном формате с указанным разрешением. |
| [set_Name](./set_name/)(const System::String\&) | Устанавливает имя изображения. Обратите внимание, что если вы измените имя изображения, которое имеет ссылки в содержимом страниц, документ может стать некорректным. В этом случае используйте метод [XImage.Rename](./rename/). |
| [ToStream](./tostream/)() | Возвращает оригинальный поток изображения. |
| [TrySetAlternativeText](./trysetalternativetext/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Устанавливает альтернативный текст для [XImage](./) на странице. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
