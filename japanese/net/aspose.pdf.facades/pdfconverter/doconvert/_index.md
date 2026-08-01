---
title: "PdfConverter.DoConvert"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfConverter メソッド。PDF ドキュメントを画像に変換するための初期処理を行います"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfconverter/doconvert/
---
## PdfConverter.DoConvert method

Pdf ドキュメントを画像に変換するための初期処理を実行します。

```csharp
public void DoConvert()
```

## 例

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

### 関連項目

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


