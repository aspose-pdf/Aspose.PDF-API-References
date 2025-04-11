---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: Метод SideBySidePdfComparer. Сравнивает две страницы. Результат сохраняется в PDF-документе, в котором сначала записывается первая страница, а затем вторая. Вы можете открыть его в Adobe Acrobat в режиме двух страниц, чтобы увидеть изменения бок о бок. Удаления отмечены на странице слева, а вставки отмечены на странице справа.
type: docs
weight: 10
url: /ru/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Сравнивает две страницы. Результат сохраняется в PDF-документе, в котором сначала записывается первая страница, а затем вторая. Вы можете открыть его в Adobe Acrobat в режиме двух страниц, чтобы увидеть изменения бок о бок. Удаления отмечены на странице слева, а вставки отмечены на странице справа.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | Page | Первая страница для сравнения. |
| page2 | Page | Вторая страница для сравнения. |
| targetPdfPath | String | Путь к PDF-файлу для сохранения результата сравнения. |
| options | SideBySideComparisonOptions | Параметры сравнения. |

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* класс [SideBySidePdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Сравнивает два документа. Страницы сравниваются по одной. Страницы сравниваемых документов копируются одна за другой в результирующий документ. Сначала первая страница из первого документа, затем первая страница из второго документа. Далее идет вторая страница из первого документа и затем вторая страница из второго документа и так далее. Вы можете открыть его в Adobe Acrobat в режиме двух страниц, чтобы увидеть изменения бок о бок. Удаления отмечены на странице слева, а вставки отмечены на странице справа.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | Document | Первый документ для сравнения. |
| document2 | Document | Второй документ для сравнения. |
| targetPdfPath | String | Путь к PDF-файлу для сохранения результата сравнения. |
| options | SideBySideComparisonOptions | Параметры сравнения. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* класс [SideBySidePdfComparer](../)
* пространство имен [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../../)