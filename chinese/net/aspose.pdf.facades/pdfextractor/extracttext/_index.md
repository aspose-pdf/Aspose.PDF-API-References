---
title: ExtractText
second_title: Aspose.PDF for .NET API 参考
description: 使用 Unicode 编码从 Pdf 文档中提取文本
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

使用 Unicode 编码从 Pdf 文档中提取文本。

```csharp
public void ExtractText()
```

### 例子

第一个示例演示如何从 PDF 文件中提取所有文本。 第二个示例演示如何将每一页的文本提取到一个 txt 文件中。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText()
extractor.GetText("D:\Text\text.txt")
```

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText();
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
extractor.ExtractText()
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### 也可以看看

* class [PdfExtractor](../../pdfextractor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfextractor)
* 部件 [Aspose.PDF](../../../)

---

## ExtractText(Encoding) {#extracttext_1}

使用指定的编码从 Pdf 文档中提取文本。

```csharp
public void ExtractText(Encoding encoding)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| encoding | Encoding | 提取文本的编码。 |

### 例子

第一个示例演示如何从 PDF 文件中提取所有文本。 第二个示例演示如何将每一页的文本提取到一个 txt 文件中。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText(Encoding.Unicode);
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText(Encoding.Unicode)
extractor.GetText("D:\Text\text.txt")
```

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

### 也可以看看

* class [PdfExtractor](../../pdfextractor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfextractor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->