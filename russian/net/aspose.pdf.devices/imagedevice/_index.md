---
title: "Класс ImageDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Devices.ImageDevice. Абстрактный класс для image devices."
type: docs
weight: 3730
url: /ru/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

Абстрактный класс для устройств изображения.

```csharp
public abstract class ImageDevice : PageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Абстрактный инициализатор для `ImageDevice` наследников, устанавливающий разрешение 150×150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением по умолчанию (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Абстрактный инициализатор для `ImageDevice` наследников. Разрешение результирующего файла изображения, см. класс [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением по умолчанию (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Выполняет некоторую операцию над заданной page, например, преобразует page в графическое изображение. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

### См. также

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


