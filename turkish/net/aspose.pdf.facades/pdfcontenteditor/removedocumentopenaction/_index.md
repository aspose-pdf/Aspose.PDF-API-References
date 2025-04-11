---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belgeden açılış eylemini kaldırır. Bu işlem, başlangıçta açık 'GoTo' eylemi kullanan birden fazla belgeyi birleştirirken faydalıdır.
type: docs
weight: 430
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction metodu

Belgeden açılış eylemini kaldırır. Bu işlem, başlangıçta açık 'GoTo' eylemi kullanan birden fazla belgeyi birleştirirken faydalıdır.

```csharp
public void RemoveDocumentOpenAction()
```

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)