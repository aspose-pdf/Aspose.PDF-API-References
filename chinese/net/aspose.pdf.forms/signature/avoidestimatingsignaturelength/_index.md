---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: 签名属性。获取和设置一个选项，表示是否避免估计签名的长度
type: docs
weight: 30
url: /zh/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength 属性

获取和设置一个选项，表示是否避免估计签名的长度。

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## 备注

在签署文档之前避免估计签名长度。用于通过 [`CustomSignHash`](../customsignhash/) 和 [`ExternalSignature`](../../externalsignature/) 进行签署。如果 [`CustomSignHash`](../customsignhash/) 返回的签名长度超过 [`DefaultSignatureLength`](../defaultsignaturelength/)，则会抛出 [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/)。默认值为 `false`。

### 另请参阅

* 类 [Signature](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)