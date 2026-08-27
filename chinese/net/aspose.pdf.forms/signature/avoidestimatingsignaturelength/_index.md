---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF for .NET API 参考"
description: "Signature 属性。获取和设置一个选项，表示是否避免估计签名的长度"
type: docs
weight: 30
url: /zh/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

获取或设置一个选项，表示是否避免估计签名的长度。

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## 备注

在签署文档之前避免估计签名长度。用于通过 [`CustomSignHash`](../customsignhash/) 和 [`ExternalSignature`](../../externalsignature/) 进行签名。如果 [`CustomSignHash`](../customsignhash/) 返回的签名长度超过 [`DefaultSignatureLength`](../defaultsignaturelength/)，则会抛出 [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/)。默认值为 `false`。

### 另请参见

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


