---
title: "Класс DicomDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Devices.DicomDevice. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат Dicom."
type: docs
weight: 3680
url: /ru/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в формате Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Инициализирует новый экземпляр класса `DicomDevice` с разрешением по умолчанию. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `DicomDevice` с указанным размером страницы, с разрешением по умолчанию (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `DicomDevice`. Разрешение результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `DicomDevice` с указанными размерами изображения, с разрешением по умолчанию (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `DicomDevice` с указанным размером страницы и разрешением. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `DicomDevice` с указанными размерами изображения и разрешением. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Преобразует страницу в Dicom и сохраняет её в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

### См. также

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


