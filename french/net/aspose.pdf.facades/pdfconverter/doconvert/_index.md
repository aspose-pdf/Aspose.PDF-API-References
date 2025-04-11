---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfConverter. Effectuer quelques travaux initiaux pour convertir un document pdf en images
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## Méthode PdfConverter.DoConvert

Effectuer quelques travaux initiaux pour convertir un document pdf en images.

```csharp
public void DoConvert()
```

## Exemples

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

### Voir aussi

* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)