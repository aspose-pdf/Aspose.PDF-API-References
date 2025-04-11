---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает ссылку на JavaScript в PDF документе
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## Метод PdfContentEditor.CreateJavaScriptLink

Создает ссылку на JavaScript в PDF документе.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| code | String | Код JavaScript. |
| rect | Rectangle | Прямоугольник для активного клика. |
| originalPage | Int32 | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный со ссылкой. |
| color | Color | Цвет прямоугольника для активного клика. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)