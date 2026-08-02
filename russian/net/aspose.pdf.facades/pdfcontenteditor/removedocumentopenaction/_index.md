---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Удаляет действие открытия из документа. Эта операция полезна при объединении нескольких документов, которые используют явное действие GoTo при запуске"
type: docs
weight: 430
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

Удаляет действие открытия из документа. Эта операция полезна при объединении нескольких документов, использующих явное действие 'GoTo' при запуске.

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


