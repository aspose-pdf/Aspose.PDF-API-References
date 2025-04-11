---
title: PdfViewer.PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer metodu. Pdf belgesini bir ayar iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin.
type: docs
weight: 340
url: /tr/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup metodu

Pdf belgesini bir ayar iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin.

```csharp
public void PrintDocumentWithSetup()
```

## Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### Ayrıca Bakınız

* sınıf [PdfViewer](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)