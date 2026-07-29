---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfXmpMetadata 方法。根据命名空间 URI 获取前缀。"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

通过命名空间 URI 获取前缀。

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceURI | String | 命名空间 URI。 |

### 返回值

前缀值。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


