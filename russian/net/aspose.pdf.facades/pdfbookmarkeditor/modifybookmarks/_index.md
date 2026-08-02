---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfBookmarkEditor метод. Изменяет заголовок закладки в соответствии с указанным заголовком закладки"
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

Изменяет заголовок закладки в соответствии с указанным заголовком закладки.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sTitle | String | Исходный заголовок закладки. |
| dTitle | String | Изменённый заголовок закладки. |

## Примеры

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


