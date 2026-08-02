---
title: "PdfContentEditor.CreateText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создаёт текстовую аннотацию в PDF‑документе."
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

Создаёт текстовую аннотацию в PDF‑документе

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| title | String | Заголовок аннотации. |
| contents | String | Содержимое аннотации. |
| open | Boolean | Флаг, указывающий, должна ли аннотация изначально отображаться открытой. |
| icon | String | Имя значка, которое будет использоваться при отображении аннотации. Это значение может быть: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана текстовая аннотация. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


