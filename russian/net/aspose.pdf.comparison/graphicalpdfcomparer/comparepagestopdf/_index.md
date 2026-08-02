---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод GraphicalPdfComparer. Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ"
type: docs
weight: 80
url: /ru/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Страница | Первая страница. |
| page2 | Страница | Вторая страница. |
| resultPdfPath | String | Путь к целевому PDF‑файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. Если resultPdfPath равен null или пустой строке. |

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Страница | Первая страница. |
| page2 | Страница | Вторая страница. |
| pdfDocument | Document | Экземпляр PDF‑документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Если сравниваемые страницы имеют разные размеры. |

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


