---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: Метод GraphicalPdfComparer. Сравнивает страницы графически. Результат сравнения помещается в PDF-документ
type: docs
weight: 80
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Сравнивает страницы графически. Результат сравнения помещается в PDF-документ.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Page | Первая страница. |
| page2 | Page | Вторая страница. |
| resultPdfPath | String | Путь к целевому PDF-файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. Если resultPdfPath равно null или пустая строка. |

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [GraphicalPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Сравнивает страницы графически. Результат сравнения помещается в PDF-документ.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Page | Первая страница. |
| page2 | Page | Вторая страница. |
| pdfDocument | Document | Экземпляр PDF-документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. |

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [Document](../../../aspose.pdf/document/)
* класс [GraphicalPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)