---
title: "Класс ImageCompressionOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Optimization.ImageCompressionOptions. Класс, содержащий набор параметров для сжатия изображений."
type: docs
weight: 8090
url: /ru/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

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
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Если этот флаг установлен в true, изображения будут сжаты в документе. Уровень сжатия указывается свойством ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Получает или задаёт кодировку, используемую для хранения изображений. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Указывает уровень сжатия изображения, когда используется флаг CompressImages. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Указывает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Если этот флаг установлен в true и CompressImages также true, изображения будут изменены в размере, если их разрешение превышает указанный параметр MaxResolution. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее стандартного, но может быть неприменимо ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые нельзя сжать более быстрым алгоритмом; это может дать лучшее сжатие, но работает медленнее, чем алгоритм \"fast\"). Версия \"Fast\" не применяется для изменения размера изображений (будет использован стандартный метод). По умолчанию — \"Standard\". |

### См. также

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


