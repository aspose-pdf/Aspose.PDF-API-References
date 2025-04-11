---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.XImage. Класс, представляющий объект изображения X
type: docs
weight: 11350
url: /ru/net/aspose.pdf/ximage/
---
## Класс XImage

Класс, представляющий объект изображения X.

```csharp
public sealed class XImage
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Если изображение содержит прозрачность, то возвращает true; в противном случае - false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Получает тип фильтра изображения. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Получает версию изображения в градациях серого. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Получает высоту изображения. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Получает флаг, указывающий, следует ли рассматривать изображение как маску изображения (см. 8.9.6, "Затемненные изображения"). Если этот флаг равен true, значение BitsPerComponent должно быть 1, а Mask и ColorSpace не должны быть указаны; незатемненные области должны быть закрашены с использованием текущего цвета, не относящегося к обводке. Значение по умолчанию: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Метаданные изображения. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Получает или задает имя изображения. Обратите внимание, что если вы измените имя изображения, на которое есть ссылки в содержимом страницы, документ может стать некорректным. В этом случае используйте метод XImage.Rename. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Добавляет маску трафарета к XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Возвращает цветовой тип изображения. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Возвращает имя изображения в его коллекции. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Извлекает необработанные данные изображения из исходного изображения. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Возвращает true, если оба изображения ссылаются на один и тот же объект. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Переименовывает изображение и заменяет все ссылки на изображение новым именем. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Сохраняет данные изображения в поток в формате JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Сохраняет изображение в поток в запрашиваемом формате. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Сохраняет данные изображения в поток в формате JPEG с указанным разрешением. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Сохраняет изображение в поток в запрашиваемом формате с указанным разрешением. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Возвращает оригинальный поток изображения. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)