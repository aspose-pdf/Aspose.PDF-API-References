---
title: "Класс GraphicalPdfComparer"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer class. Представляет класс для графического сравнения PDF‑документов. Должен использоваться для поиска небольших изменений, в основном графического характера. Для сравнения изменений текстового содержимого используйте другие классы сравнения PDF"
type: docs
weight: 3300
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

Представляет класс для графического сравнения PDF‑документов. Должен использоваться для поиска небольших изменений, в основном графических. Для сравнения изменений текстового содержимого используйте другие классы сравнения PDF.

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
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Получает и задает цвет флага изменения. Цвет по умолчанию — красный. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Получает и задает разрешение получаемых изображений. Значение по умолчанию — 150 dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Получает и задает пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они не являются значимыми для вас. Значение по умолчанию — 0 %. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Сравнивает документы графически. Результат сравнения помещается в изображения. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Сравнивает документы графически. Результат сравнения помещается в PDF‑документ. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Сравнивает страницы графически. Результат сравнения помещается в изображение. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий. |

### См. также

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


