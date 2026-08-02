---
title: "Класс XImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.XImage. Класс, представляющий объект изображения XObject."
type: docs
weight: 11540
url: /ru/net/aspose.pdf/ximage/
---
## XImage class

Класс, представляющий image X-Object.

```csharp
public sealed class XImage
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Если изображение содержит прозрачность, возвращает true; иначе — false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Получает тип фильтра изображения. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Получает градацию изображения в оттенках серого. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Получает высоту изображения. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Получает флаг, указывающий, следует ли рассматривать изображение как маску изображения (см. 8.9.6, "Masked Images"). Если этот флаг установлен в true, значение BitsPerComponent должно быть 1, а Mask и ColorSpace не должны указываться; незамаскированные области должны быть закрашены текущим цветом без обводки. Значение по умолчанию: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Метаданные изображения. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Получает или задает имя изображения. Обратите внимание, что если вы измените имя изображения, которое имеет ссылки в содержимом страниц, документ может стать некорректным. В этом случае используйте метод XImage.Rename. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Добавляет трафаретную маску к XImage. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | Возвращает список строк с альтернативным текстом для XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Возвращает тип цвета изображения. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Возвращает имя изображения в его коллекции. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Извлекает необработанные данные изображения из исходного изображения. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Возвращает true, если оба изображения ссылаются на один и тот же объект. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Переименовывает изображение и заменяет все ссылки на изображение новым именем |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Сохраняет данные изображения в поток в виде JPEG‑изображения. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Сохраняет изображение в поток в запрошенном формате. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Сохраняет данные изображения в поток в виде JPEG‑изображения с указанным разрешением. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Сохраняет изображение в поток в запрошенном формате с указанным разрешением. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Возвращает оригинальный поток изображения. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | Устанавливает альтернативный текст для XImage на странице. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


