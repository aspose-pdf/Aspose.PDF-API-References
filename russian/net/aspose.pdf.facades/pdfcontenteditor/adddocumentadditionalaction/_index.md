---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Добавляет дополнительное действие для события документа
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## Метод PdfContentEditor.AddDocumentAdditionalAction

Добавляет дополнительное действие для события документа.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Типы событий документа. |
| code | String | Код JavaScript. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)