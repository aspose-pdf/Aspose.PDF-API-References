---
title: "PdfConverter.DoConvert"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfConverter-metod. Utför vissa initiala åtgärder för att konvertera ett pdf-dokument till bilder"
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## PdfConverter.DoConvert method

Utför några initiala åtgärder för att konvertera ett PDF-dokument till bilder.

```csharp
public void DoConvert()
```

## Exempel

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

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


