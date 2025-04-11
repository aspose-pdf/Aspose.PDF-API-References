---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Удаляет действие открытия из документа. Эта операция полезна при конкатенации нескольких документов, которые используют явное действие 'GoTo' при запуске.
type: docs
weight: 430
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## Метод PdfContentEditor.RemoveDocumentOpenAction

Удаляет действие открытия из документа. Эта операция полезна при конкатенации нескольких документов, которые используют явное действие 'GoTo' при запуске.

```csharp
public void RemoveDocumentOpenAction()
```

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)