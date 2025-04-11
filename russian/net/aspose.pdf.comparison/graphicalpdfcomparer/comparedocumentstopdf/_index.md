---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: Метод GraphicalPdfComparer. Сравнивает документы графически. Результат сравнения помещается в PDF-документ
type: docs
weight: 60
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## Метод GraphicalPdfComparer.CompareDocumentsToPdf

Сравнивает документы графически. Результат сравнения помещается в PDF-документ.

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ для сравнения. |
| document2 | Document | Второй документ для сравнения. |
| resultPdfPath | String | Путь к целевому PDF-файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. Если resultPdfPath равен null или пустой строке. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [GraphicalPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)