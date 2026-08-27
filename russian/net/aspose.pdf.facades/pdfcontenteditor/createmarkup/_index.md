---
title: "PdfContentEditor.CreateMarkup"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создаёт разметочную аннотацию в PDF‑документе."
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

Создаёт разметочную аннотацию в PDF‑документе.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| type | Int32 | Тип разметочной аннотации. Может быть 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| clr | Color | Цвет разметки. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


