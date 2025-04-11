---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Заменяет указанное изображение на указанной странице PDF-документа другим изображением
type: docs
weight: 440
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## Метод PdfContentEditor.ReplaceImage

Заменяет указанное изображение на указанной странице PDF-документа другим изображением.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой изображение заменяется. |
| index | Int32 | Индекс объекта изображения, который необходимо заменить. |
| imageFile | String | Файл изображения, который будет использован для замены. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)