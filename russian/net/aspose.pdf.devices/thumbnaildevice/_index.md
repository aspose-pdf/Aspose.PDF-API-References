---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.ThumbnailDevice. Представляет устройство изображения, которое сохраняет страницы pdf документа в изображение миниатюры
type: docs
weight: 3690
url: /ru/net/aspose.pdf.devices/thumbnaildevice/
---
## Класс ThumbnailDevice

Представляет устройство изображения, которое сохраняет страницы pdf документа в изображение миниатюры.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Инициализирует новый экземпляр класса `ThumbnailDevice` с размером миниатюры по умолчанию (200x200 пикселей). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Инициализирует новый экземпляр класса `ThumbnailDevice`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Преобразует страницу в изображение миниатюры png и сохраняет его в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции над данной страницей и сохраняет результаты в файл. |

### См. также

* класс [ImageDevice](../imagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)