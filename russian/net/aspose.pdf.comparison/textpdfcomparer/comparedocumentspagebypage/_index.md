---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: Метод TextPdfComparer. Сравнивает два документа постранично
type: docs
weight: 40
url: /ru/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Сравнивает два документа постранично.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ.. |
| document2 | Document | Второй документ. |
| options | ComparisonOptions | Параметры сравнения. |

### Возвращаемое значение

Список изменений по страницам.

### См. также

* класс [DiffOperation](../../diffoperation/)
* класс [Document](../../../aspose.pdf/document/)
* класс [ComparisonOptions](../../comparisonoptions/)
* класс [TextPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Сравнивает два документа постранично. Результат сохраняется в PDF-файл.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ.. |
| document2 | Document | Второй документ. |
| options | ComparisonOptions | Параметры сравнения. |
| resultPdfDocumentPath | String | Путь к PDF-файлу для сохранения результатов сравнения. |

### Возвращаемое значение

Список изменений по страницам.

### См. также

* класс [DiffOperation](../../diffoperation/)
* класс [Document](../../../aspose.pdf/document/)
* класс [ComparisonOptions](../../comparisonoptions/)
* класс [TextPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)