---
title: "PdfContentEditor.ReplaceImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Заменяет указанное изображение на указанной странице PDF‑документа другим изображением."
type: docs
weight: 440
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

Заменяет указанное изображение на указанной странице PDF‑документа другим изображением.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой заменяется изображение. |
| index | Int32 | Индекс объекта изображения, который необходимо заменить. |
| imageFile | String | Файл изображения будет использован для замены. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


