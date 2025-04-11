---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию свободного текста в PDF документе
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## Метод PdfContentEditor.CreateFreeText

Создает аннотацию свободного текста в PDF документе

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана текстовая аннотация. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)