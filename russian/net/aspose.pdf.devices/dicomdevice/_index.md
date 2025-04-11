---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.DicomDevice. Представляет устройство изображения, которое помогает сохранять страницы pdf документа в формате Dicom
type: docs
weight: 3560
url: /ru/net/aspose.pdf.devices/dicomdevice/
---
## Класс DicomDevice

Представляет устройство изображения, которое помогает сохранять страницы pdf документа в формате Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Инициализирует новый экземпляр класса `DicomDevice` с разрешением по умолчанию. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `DicomDevice` с заданным размером страницы, с разрешением по умолчанию (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `DicomDevice`. Разрешение для результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `DicomDevice` с заданными размерами изображения, с разрешением по умолчанию (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `DicomDevice` с заданным размером страницы и разрешением. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `DicomDevice` с заданными размерами изображения и разрешением. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Преобразует страницу в Dicom и сохраняет ее в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции на заданной странице и сохраняет результаты в файл. |

### См. также

* класс [ImageDevice](../imagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)