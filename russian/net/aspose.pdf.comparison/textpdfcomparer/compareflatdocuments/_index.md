---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextPdfComparer. Сравнивает два документа постранично. Документы сравниваются в целом. Перед сравнением текста тексты страниц документа объединяются в один текст."
type: docs
weight: 50
url: /ru/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Сравнивает два документа постранично. Документы сравниваются как единое целое. Перед сравнением текста тексты страниц документов объединяются в один текст.

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

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Сравнивает два документа постранично. Результат сохраняется в PDF‑файле. Документы сравниваются как единое целое. Перед сравнением текста тексты страниц документов объединяются в один текст.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ. |
| document2 | Document | Второй документ. |
| options | ComparisonOptions | Параметры сравнения. |
| resultPdfDocumentPath | String | Путь к PDF‑файлу для сохранения результатов сравнения. |

### Возвращаемое значение

Список изменений.

### См. также

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


