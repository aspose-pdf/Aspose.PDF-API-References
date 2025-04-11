---
title: PdfConverter.DoConvert
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 方法。进行一些初步工作以将 pdf 文档转换为图像
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## PdfConverter.DoConvert 方法

进行一些初步工作以将 pdf 文档转换为图像。

```csharp
public void DoConvert()
```

## 示例

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

### 另请参阅

* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)