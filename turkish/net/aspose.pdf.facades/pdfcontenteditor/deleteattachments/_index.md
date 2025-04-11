---
title: PdfContentEditor.DeleteAttachments
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesindeki tüm ekleri siler
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## PdfContentEditor.DeleteAttachments metodu

PDF belgesindeki tüm ekleri siler.

```csharp
public void DeleteAttachments()
```

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)