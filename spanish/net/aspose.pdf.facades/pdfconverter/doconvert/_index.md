---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Realiza algunos trabajos iniciales para convertir un documento pdf a imágenes
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## Método PdfConverter.DoConvert

Realiza algunos trabajos iniciales para convertir un documento pdf a imágenes.

```csharp
public void DoConvert()
```

## Ejemplos

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

### Ver También

* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)