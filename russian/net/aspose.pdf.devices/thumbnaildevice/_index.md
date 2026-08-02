---
title: "Класс ThumbnailDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Devices.ThumbnailDevice class. Представляет устройство изображения, которое сохраняет страницы PDF‑документа в изображение Thumbnail"
type: docs
weight: 3810
url: /ru/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Представляет устройство изображения, которое сохраняет страницы pdf‑документа в миниатюрное изображение.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Инициализирует новый экземпляр класса `ThumbnailDevice` с размером изображения‑миниатюры по умолчанию (200×200 пикселей). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Инициализирует новый экземпляр класса `ThumbnailDevice`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим отображения формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Преобразует page в Bitmap. |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Преобразует страницу в изображение‑миниатюру png и сохраняет её в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

### См. также

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


