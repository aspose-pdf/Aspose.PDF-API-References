---
title: "PdfXmpMetadata.Item"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfXmpMetadata 属性。按键获取或设置值"
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

按键获取或设置值。

```csharp
public XmpValue this[string key] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 键 | 用于获取/设置的键名。 |

### 返回值

按键获取的对象

## 示例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### 另请参见

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

通过键获取 XMP 元数据的值。

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 键 | 值的键。 |

### 返回值

来自 XMP 元数据的值。

## 示例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### 另请参见

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


