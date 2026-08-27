---
title: "PdfConverter.BindPdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfConverter 方法。绑定用于转换的 PDF 文件"
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdfconverter/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

绑定一个 Pdf 文件以进行转换。

```csharp
public override void BindPdf(string inputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | PDF 文件。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

绑定一个 Pdf 流以进行转换。

```csharp
public override void BindPdf(Stream inputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | PDF 流。 |

### 另请参见

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

将 PDF 文档绑定到 [`PdfConverter`](../) 实例以进行进一步处理。

```csharp
public override void BindPdf(Document srcDoc)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | Document | 表示要绑定的源 PDF 的 [`Document`](../../../aspose.pdf/document/) 对象。 |

## 备注

此方法使用指定的 PDF 文档初始化 [`PdfConverter`](../)。如果文档中存在，还会处理动态 XFA 表单。

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


