---
title: PrintDocumentWithSetup
second_title: Aspose.PDF for .NET API Referansı
description: Pdf belgesini bir kurulum iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin.
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Pdf belgesini bir kurulum iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin.

```csharp
public void PrintDocumentWithSetup()
```

### Örnekler

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         // dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true;         // dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
iewer.PrintDocumentWithSetup();
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")   
iewer.AutoResize = true          'dosyayı ayarlanmış boyutta yazdır
iewer.AutoRotate = true          'dosyayı ayarlanmış rotasyonla yazdır
iewer.PrintPageDialog=false;// yazdırırken sayfa numarası diyaloğunu oluşturma
iewer.PrintDocumentWithSetup()
iewer.ClosePdfFile()
```

### Ayrıca bakınız

* class [PdfViewer](../../pdfviewer)
* ad alanı [Aspose.Pdf.Facades](../../pdfviewer)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->