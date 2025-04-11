---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter metodu. Bir pdf belgesini görüntülere dönüştürmek için bazı başlangıç çalışmaları yapar
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## PdfConverter.DoConvert metodu

Bir pdf belgesini görüntülere dönüştürmek için bazı başlangıç çalışmaları yapar.

```csharp
public void DoConvert()
```

## Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix)
	imageCount = imageCount + 1
End While
```

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)