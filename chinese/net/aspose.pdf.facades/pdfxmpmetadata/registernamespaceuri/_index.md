---
title: RegisterNamespaceURI
second_title: Aspose.PDF for .NET API 参考
description: 注册命名空间 URI
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

注册命名空间 URI。

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| prefix | String | 前缀。 |
| namespaceURI | String | 命名空间 URI。 |

### 例子

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### 也可以看看

* class [PdfXmpMetadata](../../pdfxmpmetadata)
* 命名空间 [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->