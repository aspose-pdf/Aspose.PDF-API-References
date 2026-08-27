---
title: "PdfExtractor.HasNextPageText"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。指示是否可以获取更多文本"
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText method

指示是否可以获取更多文本。

```csharp
public bool HasNextPageText()
```

### 返回值

是否可以获取更多文本，true 表示可以，false 表示不可以。

## 示例

示例演示了在文本提取场景中 `HasNextPageText` 属性的用法。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


