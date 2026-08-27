---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfXmpMetadata 方法。通过前缀获取命名空间 URI。"
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

通过前缀获取命名空间 URI。

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | String | 前缀。 |

### 返回值

命名空间 URI。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


