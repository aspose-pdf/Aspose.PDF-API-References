---
title: "PdfFileSignature.Certify"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSignature 方法。使用 MDP 签名对文档进行认证。签名原因、联系信息和位置等数据必须通过 Signature 对象 sig 的相应属性提供。"
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

使用 MDP 签名对 document 进行认证。签名原因、联系信息和位置等数据必须通过 Signature 对象 sig 的相应属性提供。

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | Int32 | 签名所在的页面。 |
| SigReason | String | 签名的原因。 |
| SigContact | String | 签名的联系人。 |
| SigLocation | String | 签名的位置。 |
| 可见 | Boolean | 签名的可见性。 |
| annotRect | Rectangle | 签名的矩形区域。 |
| docMdpSignature | DocMDPSignature | 签名的文档 MDP 类型。 |

### 另请参见

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

使用已放置在现有签名字段中的 MDP 签名对 document 进行认证。签名之前，签名字段必须为空，即字段不得包含签名字典。因此 pdf document 已经拥有签名字段，您无需提供签名的放置位置，对应的 page 和 rectangle 将从通过签名名称（参见 sigName 参数）找到的签名字段中获取。

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sigName | String | 签名字段的名称。 |
| docMdpSignature | DocMDPSignature | 签名的类型，可为 [`PKCS1`](../../../aspose.pdf.forms/pkcs1/)、[`PKCS7`](../../../aspose.pdf.forms/pkcs7/) 或 [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/)。 |

### 另请参见

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


