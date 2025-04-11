---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfConverter. Выполните некоторые начальные работы для преобразования pdf-документа в изображения
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## Метод PdfConverter.DoConvert

Выполните некоторые начальные работы для преобразования pdf-документа в изображения.

```csharp
public void DoConvert()
```

## Примеры

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

### См. также

* класс [PdfConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)