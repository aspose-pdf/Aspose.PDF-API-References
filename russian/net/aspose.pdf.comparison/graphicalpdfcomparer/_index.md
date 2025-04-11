---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Comparison.GraphicalPdfComparer. Представляет класс для графического сравнения PDF-документов. Должен использоваться для поиска небольших изменений, в основном графического характера. Для сравнения изменений текстового содержимого используйте другие классы сравнения PDF.
type: docs
weight: 3190
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Класс GraphicalPdfComparer

Представляет класс для графического сравнения PDF-документов. Должен использоваться для поиска небольших изменений, в основном графического характера. Для сравнения изменений текстового содержимого используйте другие классы сравнения PDF.

```csharp
public class GraphicalPdfComparer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Получает и устанавливает цвет флага изменения. Цвет по умолчанию - красный. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Получает и устанавливает разрешение результирующих изображений. Значение по умолчанию - 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Получает и устанавливает пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они незначительны для вас. Значение по умолчанию - 0%. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Графически сравнивает документы. Результат сравнения помещается в изображения. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Графически сравнивает документы. Результат сравнения помещается в PDF-документ. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Графически сравнивает страницы. Результат сравнения помещается в изображение. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Графически сравнивает страницы. Результат сравнения помещается в PDF-документ. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Графически сравнивает страницы. Результат сравнения помещается в PDF-документ. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий. |

### См. также

* пространство имен [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../)