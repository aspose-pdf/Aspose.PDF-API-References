---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfBookmarkEditor. Изменяет заголовок закладки в соответствии с указанным заголовком закладки
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## Метод PdfBookmarkEditor.ModifyBookmarks

Изменяет заголовок закладки в соответствии с указанным заголовком закладки.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sTitle | String | Исходный заголовок закладки. |
| dTitle | String | Измененный заголовок закладки. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfBookmarkEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)