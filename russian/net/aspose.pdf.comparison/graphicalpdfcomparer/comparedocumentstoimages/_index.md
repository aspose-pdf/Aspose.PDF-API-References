---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: Метод GraphicalPdfComparer. Сравнивает документы графически. Результат сравнения помещается в изображения
type: docs
weight: 50
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## Метод GraphicalPdfComparer.CompareDocumentsToImages

Сравнивает документы графически. Результат сравнения помещается в изображения.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ для сравнения. |
| document2 | Document | Второй документ для сравнения. |
| targetDirectory | String | Директория для сохранения результатов сравнения. |
| fileNamePrefix | String | Префикс имени изображений. |
| imageFormat | ImageFormat | Формат изображения для сохранения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. Если targetDirectory равно null или пустая строка. Если fileNamePrefix равно null или пустая строка. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [GraphicalPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)