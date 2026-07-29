---
title: "PdfExtractor.GetNextPageText"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。将单页文本保存到文件。"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

将单页文本保存到文件中。

```csharp
public void GetNextPageText(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 用于保存文本的文件路径和名称。 |

## 示例

示例演示了 GetNextPageText 方法在文本提取场景中的使用。

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

---

## GetNextPageText(Stream) {#getnextpagetext}

将单页文本保存到流中。

```csharp
public void GetNextPageText(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存文本的流。 |

## 示例

示例演示了 `GetNextPageText` 方法在文本提取场景中的使用。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    FileStream fs = new FileStream(prefix + pageCount + suffix, FileMode.Create);
    extractor.GetNextPageText(prefix + pageCount + suffix);
    fs.Close();
    pageCount++;
}
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


