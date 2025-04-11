---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfConverter. Esegui alcune operazioni iniziali per convertire un documento pdf in immagini
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## Metodo PdfConverter.DoConvert

Esegui alcune operazioni iniziali per convertire un documento pdf in immagini.

```csharp
public void DoConvert()
```

## Esempi

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

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)