---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfConverter. Melakukan beberapa pekerjaan awal untuk mengonversi dokumen pdf menjadi gambar
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## Metode PdfConverter.DoConvert

Melakukan beberapa pekerjaan awal untuk mengonversi dokumen pdf menjadi gambar.

```csharp
public void DoConvert()
```

## Contoh

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

### Lihat Juga

* kelas [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)