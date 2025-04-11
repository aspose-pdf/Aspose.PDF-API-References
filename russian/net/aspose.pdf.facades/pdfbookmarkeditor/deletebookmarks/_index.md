---
title: PdfBookmarkEditor.DeleteBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfBookmarkEditor. Удаляет все закладки PDF-документа
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Удаляет все закладки PDF-документа.

```csharp
public void DeleteBookmarks()
```

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Удаляет закладку PDF-документа.

```csharp
public void DeleteBookmarks(string title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | String | Заголовок удаленной закладки. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)