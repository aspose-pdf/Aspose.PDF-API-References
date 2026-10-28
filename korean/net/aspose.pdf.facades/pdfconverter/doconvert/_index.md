---
title: "PdfConverter.DoConvert"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfConverter 메서드. pdf 문서를 이미지로 변환하기 위한 초기 작업을 수행합니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## PdfConverter.DoConvert method

pdf 문서를 이미지로 변환하기 위한 초기 작업을 수행합니다.

```csharp
public void DoConvert()
```

## 예제

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

### 또 보기

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


