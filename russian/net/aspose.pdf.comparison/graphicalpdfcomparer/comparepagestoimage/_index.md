---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: Метод GraphicalPdfComparer. Сравнивает страницы графически. Результат сравнения помещается в изображение
type: docs
weight: 70
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## Метод GraphicalPdfComparer.ComparePagesToImage

Сравнивает страницы графически. Результат сравнения помещается в изображение.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Page | Первая страница для сравнения. |
| page2 | Page | Вторая страница для сравнения. |
| resultImagePath | String | Путь к целевому файлу изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. Если resultImagePath равно null или пустой строке. Неизвестный формат сохранения изображения. |

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [GraphicalPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)