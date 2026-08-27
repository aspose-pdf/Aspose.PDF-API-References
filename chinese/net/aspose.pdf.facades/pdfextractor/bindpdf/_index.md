---
title: "PdfExtractor.BindPdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfExtractor 方法。绑定输入的 PDF 文件"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

绑定输入 PDF 文件。

```csharp
public override void BindPdf(string inputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 要绑定的 PDF 文件 |

## 示例

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

从流绑定 PDF 文档。

```csharp
public override void BindPdf(Stream inputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 包含 PDF 文档数据的流 |

## 示例

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### 另请参见

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


