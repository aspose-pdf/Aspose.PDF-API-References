---
title: PdfContentEditor.DeleteAttachments
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Удаляет все вложения в PDF документе
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## Метод PdfContentEditor.DeleteAttachments

Удаляет все вложения в PDF документе.

```csharp
public void DeleteAttachments()
```

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)