---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfContentEditor метод. Создает ссылку на JavaScript в PDF Document"
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

Создаёт ссылку на JavaScript в PDF‑документе.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| code | String | JavaScript код. |
| rect | Rectangle | Прямоугольник для активного клика. |
| originalPage | Int32 | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


