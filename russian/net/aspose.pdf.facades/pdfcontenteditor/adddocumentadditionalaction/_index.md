---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Добавляет дополнительное действие для события document."
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

Добавляет дополнительное действие для события документа.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | String | Типы событий document. |
| code | String | Код JavaScript. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


