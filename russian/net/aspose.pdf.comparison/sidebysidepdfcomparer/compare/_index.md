---
title: "SideBySidePdfComparer.Compare"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод SideBySidePdfComparer. Сравнивает две страницы. Результат сохраняется в PDF‑документе, в котором первая страница записана первой, а затем вторая. Вы можете открыть его в Adobe Acrobat в режиме двухстраничного просмотра, чтобы увидеть изменения рядом. Удаления отмечены на странице слева, а вставки — на странице справа."
type: docs
weight: 10
url: /ru/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Сравнивает две страницы. Результат сохраняется в PDF‑документе, где первая страница записывается первой, затем вторая. Вы можете открыть его в Adobe Acrobat в режиме двухстраничного просмотра, чтобы увидеть изменения рядом. Удаления отмечаются на странице слева, вставки — на странице справа.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Страница | Первая страница для сравнения. |
| page2 | Страница | Первая страница для сравнения. |
| targetPdfPath | String | Путь к PDF‑файлу для сохранения результата сравнения. |
| options | SideBySideComparisonOptions | Параметры сравнения. |

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Сравнивает два документа. Страницы сравниваются поочерёдно. Страницы сравниваемых документов копируются одна за другой в результирующий документ. Сначала первая страница первого документа, затем первая страница второго документа. Далее вторая страница первого документа и затем вторая страница второго документа и т.д. Вы можете открыть полученный документ в Adobe Acrobat в режиме двухстраничного просмотра, чтобы увидеть изменения рядом. Удаления отмечаются на странице слева, вставки — на странице справа.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ для сравнения. |
| document2 | Document | Второй документ для сравнения. |
| targetPdfPath | String | Путь к PDF‑файлу для сохранения результата сравнения. |
| options | SideBySideComparisonOptions | Параметры сравнения. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


