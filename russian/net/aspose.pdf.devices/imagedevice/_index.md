---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.ImageDevice. Абстрактный класс для устройств изображений
type: docs
weight: 3610
url: /ru/net/aspose.pdf.devices/imagedevice/
---
## Класс ImageDevice

Абстрактный класс для устройств изображений.

```csharp
public abstract class ImageDevice : PageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Абстрактный инициализатор для потомков `ImageDevice`, устанавливает разрешение 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением по умолчанию (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Абстрактный инициализатор для потомков `ImageDevice`. Разрешение для результирующего файла изображения, см. класс [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением по умолчанию (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Выполняет некоторые операции на заданной странице, например, преобразует страницу в графическое изображение. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции на заданной странице и сохраняет результаты в файл. |

### См. также

* класс [PageDevice](../pagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)