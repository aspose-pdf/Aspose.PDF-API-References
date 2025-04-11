---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfBookmarkEditor. Создает закладку для указанной страницы
type: docs
weight: 20
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Создает закладку для указанной страницы.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmarkName | String | Указанное имя закладки. |
| pageNumber | Int32 | Указанная целевая страница. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Создает закладки для указанных страниц.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmarkName | String[] | Массив заголовков закладок. |
| pageNumber | Int32[] | Массив целевых страниц закладок. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)