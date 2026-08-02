---
title: "Класс ImagesDifference"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Comparison.ImagesDifference. Представляет класс результата сравнения двух страниц PDF"
type: docs
weight: 3340
url: /ru/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

Представляет класс результата сравнения двух PDF‑страниц.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Получает массив различий. Этот массив похож на исходный массив данных изображения, полученный в результате метода LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | Высота различий. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Получает изображение первой сравниваемой страницы. Формат пикселей изображения — 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Шаг (stride) данных изображения различий. |

## Методы

| Имя | Описание |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Преобразует массив различий в растровое изображение, используя указанные цвета. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Выполняет все необходимые операции очистки перед уничтожением объекта. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Возвращает новое растровое изображение, представляющее целевое изображение, применяя массив различий к исходному изображению. |

### См. также

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


