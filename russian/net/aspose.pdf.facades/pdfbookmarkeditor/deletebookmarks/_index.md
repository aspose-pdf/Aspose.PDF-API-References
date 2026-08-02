---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfBookmarkEditor метод. Удаляет все закладки PDF‑документа"
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Удаляет все закладки PDF document.

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

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Удаляет закладку PDF document.

```csharp
public void DeleteBookmarks(string title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | String | Заголовок удалённой закладки. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


