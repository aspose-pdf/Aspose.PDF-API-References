---
title: "PdfContentEditor.CreateFreeText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создаёт свободную текстовую аннотацию в PDF‑документе."
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

Создаёт аннотацию свободного текста в PDF‑документе

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана текстовая аннотация. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


