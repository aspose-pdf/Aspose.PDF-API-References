---
title: PngDevice
second_title: Aspose.PDF для справочника API .NET
description: Представляет устройство изображения которое помогает сохранять страницы PDF-документа в png.
type: docs
weight: 1750
url: /ru/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

Представляет устройство изображения, которое помогает сохранять страницы PDF-документа в png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngDevice](pngdevice#constructor)() | Инициализирует новый экземпляр[`PngDevice`](../pngdevice) класс с разрешением по умолчанию. |
| [PngDevice](pngdevice#constructor_2)(PageSize) | Инициализирует новый экземпляр[`PngDevice`](../pngdevice) class с предоставленным размером страницы, разрешением по умолчанию (=150). |
| [PngDevice](pngdevice#constructor_1)(Resolution) | Инициализирует новый экземпляр[`PngDevice`](../pngdevice) класс.  Разрешение результирующего файла изображения, см.[`Resolution`](../resolution) класс. |
| [PngDevice](pngdevice#constructor_4)(int, int) | Инициализирует новый экземпляр[`PngDevice`](../pngdevice) класс с предоставленными размерами изображения, разрешение по умолчанию (= 150). |
| [PngDevice](pngdevice#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр[`PngDevice`](../pngdevice)класс с предоставленным размером страницы и разрешением . |
| [PngDevice](pngdevice#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр[`PngDevice`](../pngdevice) класс с предоставленными размерами изображения и разрешением . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Получает или задает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Получает или задает режим представления формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Получает высоту вывода изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Получает разрешение изображения. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Получает ширину вывода изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process#process)(Page, Stream) | Преобразует страницу в png и сохраняет ее в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Выполняет некоторую операцию на данной странице и сохраняет результаты в файл. |

### Смотрите также

* class [ImageDevice](../imagedevice)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->