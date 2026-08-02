---
title: "PdfContentEditor.CreatePopup"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfContentEditor метод. Создает всплывающую аннотацию в PDF‑документе."
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

Создаёт всплывающую аннотацию в PDF‑документе.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| open | Boolean | Флаг, указывающий, должна ли всплывающая аннотация изначально отображаться открытой. |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


