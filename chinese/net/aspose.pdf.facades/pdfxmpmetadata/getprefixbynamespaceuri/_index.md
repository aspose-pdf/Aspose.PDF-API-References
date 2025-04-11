---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 方法。通过命名空间 URI 获取前缀
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI 方法

通过命名空间 URI 获取前缀。

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceURI | 字符串 | 命名空间 URI。 |

### 返回值

前缀值。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### 另请参阅

* 类 [PdfXmpMetadata](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)