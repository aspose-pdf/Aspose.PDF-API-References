---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 方法。将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 文件
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 文件。

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | 字符串 | 保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |

## 示例

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### 另请参见

* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 文件。

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | 字符串 | 保存 TIFF 图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |

### 另请参见

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 流。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位为像素。 |
| imageHeight | Int32 | 图像高度，单位为像素。 |

### 另请参见

* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 流。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 保存 TIFF 图像的流。 |
| pageSize | PageSize | 图像的页面大小。 |

### 另请参见

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 文件。

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | 字符串 | 保存 TIFF 图像的流。 |

## 示例

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### 另请参见

* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

将 PDF 文档的每一页转换为图像，并将图像保存到单个 TIFF ClassF 流。

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 保存 TIFF 图像的流。 |

### 另请参见

* 类 [PdfConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)