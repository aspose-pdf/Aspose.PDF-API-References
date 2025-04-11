---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: Метод TextPdfComparer. Сравнивает два документа постранично. Документы сравниваются целиком. Перед сравнением текста тексты страниц документа объединяются в один текст
type: docs
weight: 50
url: /ru/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Сравнивает два документа постранично. Документы сравниваются целиком. Перед сравнением текста тексты страниц документа объединяются в один текст.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ. |
| document2 | Document | Второй документ. |
| options | ComparisonOptions | Параметры сравнения. |

### Возвращаемое значение

Список изменений.

### См. также

* класс [DiffOperation](../../diffoperation/)
* класс [Document](../../../aspose.pdf/document/)
* класс [ComparisonOptions](../../comparisonoptions/)
* класс [TextPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Сравнивает два документа постранично. Результат сохраняется в PDF-файл. Документы сравниваются целиком. Перед сравнением текста тексты страниц документа объединяются в один текст.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ. |
| document2 | Document | Второй документ. |
| options | ComparisonOptions | Параметры сравнения. |
| resultPdfDocumentPath | String | Путь к PDF-файлу для сохранения результатов сравнения. |

### Возвращаемое значение

Список изменений.

### См. также

* класс [DiffOperation](../../diffoperation/)
* класс [Document](../../../aspose.pdf/document/)
* класс [ComparisonOptions](../../comparisonoptions/)
* класс [TextPdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)