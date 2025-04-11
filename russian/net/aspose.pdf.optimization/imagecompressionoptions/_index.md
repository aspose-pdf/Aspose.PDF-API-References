---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Optimization.ImageCompressionOptions. Класс содержит набор параметров для сжатия изображений
type: docs
weight: 7950
url: /ru/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Класс ImageCompressionOptions

Класс содержит набор параметров для сжатия изображений.

```csharp
public class ImageCompressionOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Если этот флаг установлен в true, изображения будут сжаты в документе. Уровень сжатия задается свойством ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Получает или задает кодировку, используемую для хранения изображений. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Указывает уровень сжатия изображения, когда используется флаг CompressIamges. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Указывает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабироваться. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Если этот флаг установлен в true и CompressImages равно true, изображения будут изменены в размере, если разрешение изображения больше, чем указанный параметр MaxResolution. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее стандартного, но может не применяться ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом, это может дать лучшее сжатие, но медленнее, чем алгоритм "быстрый". Версия "Быстрый" не применяется для изменения размера изображений (будет использован стандартный метод). По умолчанию "Стандартный". |

### См. также

* пространство имен [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* сборка [Aspose.PDF](../../)