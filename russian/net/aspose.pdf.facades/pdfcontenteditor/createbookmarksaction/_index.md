---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создаёт закладку с указанным действием."
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

Создаёт закладку с указанным действием.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | String | Заголовок закладки. |
| color | Color | Цвет заголовка закладки. |
| boldFlag | Boolean | Флаг жирного начертания. |
| italicFlag | Boolean | Флаг курсивного начертания. |
| file | String | Другой файл или приложение, необходимое, когда тип действия — \"GoToR\" или \"Launch\". |
| actionType | String | Тип действия. Значение может быть: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Локальный пункт назначения или удалённый пункт назначения, или URL. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


