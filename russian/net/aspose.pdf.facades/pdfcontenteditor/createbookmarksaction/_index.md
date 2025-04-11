---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает закладку с указанным действием
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## Метод PdfContentEditor.CreateBookmarksAction

Создает закладку с указанным действием.

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
| file | String | Другой файл или приложение, необходимое, когда тип действия "GoToR" или "Launch". |
| actionType | String | Тип действия. Значение может быть: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Локальное назначение или удаленное назначение или URL. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)