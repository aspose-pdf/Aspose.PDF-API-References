---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 方法。使用 MDP 签名对文档进行认证。签名原因、联系人和位置等数据必须通过 Signature 对象 sig 的相应属性提供。
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

使用 MDP 签名对文档进行认证。签名原因、联系人和位置等数据必须通过 Signature 对象 sig 的相应属性提供。

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 签名所在的页面。 |
| SigReason | String | 签名的原因。 |
| SigContact | String | 签名的联系人。 |
| SigLocation | String | 签名的位置。 |
| visible | Boolean | 签名的可见性。 |
| annotRect | Rectangle | 签名的矩形区域。 |
| docMdpSignature | DocMDPSignature | 签名的文档 MDP 类型。 |

### 另见

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

使用已存在的签名字段中的 MDP 签名对文档进行认证。在签名之前，签名字段必须为空，即字段中不得包含签名字典。因此，PDF 文档已经有签名字段，您不需要提供签名的盖章位置，相应的页面和矩形区域将从通过签名名称找到的签名字段中获取（参见 sigName 参数）。

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sigName | String | 签名字段的名称。 |
| docMdpSignature | DocMDPSignature | 签名的类型，可以是 [`PKCS1`](../../../aspose.pdf.forms/pkcs1/)、[`PKCS7`](../../../aspose.pdf.forms/pkcs7/) 和 [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### 另见

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)