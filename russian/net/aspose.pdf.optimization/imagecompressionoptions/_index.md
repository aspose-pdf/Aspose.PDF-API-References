---
title: ImageCompressionOptions
second_title: Aspose.PDF для справочника API .NET
description: Класс содержит набор опций для сжатия изображений.
type: docs
weight: 5710
url: /ru/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

Класс содержит набор опций для сжатия изображений.

```csharp
public class ImageCompressionOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages) { get; set; } | Если для этого флага установлено значение true, изображения в документе будут сжаты. уровень сжатия задается свойством ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding) { get; set; } | Получает или задает кодировку, используемую для хранения изображений. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality) { get; set; } | Указывает уровень сжатия изображения при использовании флага CompressIamges. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution) { get; set; } | Определяет максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages) { get; set; } | Если для этого флага установлено значение true, а для параметра CompressImages установлено значение true, размеры изображений будут изменены, если разрешение изображения больше указанного параметра MaxResolution. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version) { get; set; } | Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее стандартного, но может быть применимо не ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом, это может обеспечить наилучшее сжатие, но более медленное, чем "быстрый" алгоритм. Версия "Быстрая" не применима для изменения размера изображений (будет использоваться стандартный метод). По умолчанию используется "Стандартная". |

### Смотрите также

* пространство имен [Aspose.Pdf.Optimization](../../aspose.pdf.optimization)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->