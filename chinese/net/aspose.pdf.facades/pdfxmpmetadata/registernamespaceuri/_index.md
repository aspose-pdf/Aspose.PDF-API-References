---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 方法。注册命名空间 URI
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI 方法

注册命名空间 URI。

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | 字符串 | 前缀。 |
| namespaceURI | 字符串 | 命名空间 URI。 |

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### 另请参见

* 类 [PdfXmpMetadata](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)