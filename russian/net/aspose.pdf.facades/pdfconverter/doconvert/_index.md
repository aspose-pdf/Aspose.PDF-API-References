---
title: DoConvert
second_title: Aspose.PDF для справочника API .NET
description: Выполните некоторые начальные действия по преобразованию документа PDF в изображения.
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## PdfConverter.DoConvert method

Выполните некоторые начальные действия по преобразованию документа PDF в изображения.

```csharp
public void DoConvert()
```

### Примеры

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

### Смотрите также

* class [PdfConverter](../../pdfconverter)
* пространство имен [Aspose.Pdf.Facades](../../pdfconverter)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->