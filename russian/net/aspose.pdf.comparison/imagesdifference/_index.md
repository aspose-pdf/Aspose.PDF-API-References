---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Comparison.ImagesDifference. Представляет результат сравнения двух страниц PDF
type: docs
weight: 3230
url: /ru/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

Представляет результат сравнения двух страниц PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Получает массив различий. Этот массив аналогичен исходному массиву данных изображения, полученному в результате метода LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | Высота различия. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Получает изображение первой сравниваемой страницы. Изображение имеет пиксельный формат 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Шаг данных изображения различия. |

## Methods

| Name | Description |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Преобразует массив различий в растровое изображение, используя указанные цвета. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Выполняет необходимые операции очистки перед уничтожением объекта. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Возвращает новое растровое изображение, представляющее целевое изображение, применяя массив различий к исходному изображению. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)