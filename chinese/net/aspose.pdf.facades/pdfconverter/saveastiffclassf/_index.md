---
title: SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API 参考
description: 将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中。

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 用于保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |

### 例子

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

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中。

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 用于保存 TIFF 图像的流。 |
| pageSize | PageSize | 图片的页面大小。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流中。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存 TIFF 图像的流。 |
| imageWidth | Int32 | 图像宽度，单位是像素。 |
| imageHeight | Int32 | 图像高度，单位是像素。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流中。

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存 TIFF 图像的流。 |
| pageSize | PageSize | 图片的页面大小。 |

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 文件中。

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | String | 用于保存 TIFF 图像的流。 |

### 例子

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

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

将 pdf 文档的每一页转换为图像并将图像保存到单个 TIFF ClassF 流中。

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 用于保存 TIFF 图像的流。 |

### 也可以看看

* class [PdfConverter](../../pdfconverter)
* 命名空间 [Aspose.Pdf.Facades](../../pdfconverter)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->