---
title: "Stamp.BindPdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "Stamp 方法。设置将用作印章的 PDF 文件和页码"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

设置将用作印章的 PDF 文件及页码。

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfFile | String | PDF 文件的路径。 |
| pageNumber | Int32 | PDF 文件中的页码 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//第一页将用作印章。
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

设置将用作印章的 PDF 文件及页码。

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | Stream | 包含 PDF 文档的流。 |
| pageNumber | Int32 | 将用作印章的文档页面索引。 |

## 示例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//第一页将用作印章。
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 另请参见

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


