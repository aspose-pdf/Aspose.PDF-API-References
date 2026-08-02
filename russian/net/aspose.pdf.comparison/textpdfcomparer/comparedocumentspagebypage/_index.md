---
title: "TextPdfComparer.CompareDocumentsPageByPage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextPdfComparer. Сравнивает два документа постранично."
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

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Сравнивает два документа постранично. Результат сохраняется в PDF‑файле.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ.. |
| document2 | Document | Второй документ. |
| options | ComparisonOptions | Параметры сравнения. |
| resultPdfDocumentPath | String | Путь к PDF‑файлу для сохранения результатов сравнения. |

### Возвращаемое значение

Список изменений по страницам.

### См. также

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


