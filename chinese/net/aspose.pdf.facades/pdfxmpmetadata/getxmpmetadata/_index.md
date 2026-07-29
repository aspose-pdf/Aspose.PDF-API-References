---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfXmpMetadata 方法。以 XML 格式获取输入 PDF 的 XmpMetadata"
type: docs
weight: 190
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

以 XML 格式获取输入 PDF 的 XmpMetadata。

```csharp
public byte[] GetXmpMetadata()
```

### 返回值

XmpMetadata 的字节。

## 示例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

根据元数据名称获取输入 PDF 的 XmpMetadata 的一部分。

```csharp
public byte[] GetXmpMetadata(string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | 元数据名称。 |

### 返回值

元数据的字节。

## 示例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


