---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод GraphicalPdfComparer. Сравнивает документы графически. Результат сравнения помещается в изображения"
type: docs
weight: 50
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

Сравнивает документы графически. Результат сравнения помещается в изображения.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ для сравнения. |
| document2 | Document | Второй документ для сравнения. |
| targetDirectory | String | Каталог для сохранения результатов сравнения. |
| fileNamePrefix | String | Префикс имени изображений. |
| imageFormat | ImageFormat | Формат изображения для сохранения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. Если targetDirectory равно null или пустой строке. Если fileNamePrefix равно null или пустой строке. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


