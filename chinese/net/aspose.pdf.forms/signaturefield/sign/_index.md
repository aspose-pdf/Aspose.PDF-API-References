---
title: "SignatureField.Sign"
second_title: "Aspose.PDF for .NET API 参考"
description: "SignatureField 方法。使用此签名字段对文档进行签名"
type: docs
weight: 60
url: /zh/net/aspose.pdf.forms/signaturefield/sign/
---
## Sign(Signature, Stream, string) {#sign_1}

使用此签名字段签署文档。

```csharp
public void Sign(Signature signature, Stream pfx, string pass)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | Signature | 签名对象，请参阅 [`PKCS1`](../../pkcs1/)、[`PKCS7`](../../pkcs7/)、[`PKCS7Detached`](../../pkcs7detached/)。 |
| pfx | Stream | 包含证书的流。 |
| 通过 | String | 用于访问 *pfx* 中私钥的密码。 |

### 另请参见

* class [Signature](../../signature/)
* class [SignatureField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Sign(Signature) {#sign}

使用此签名字段对文档进行签名。

```csharp
public void Sign(Signature signature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | Signature | 签名对象，请参阅 [`PKCS1`](../../pkcs1/)、[`PKCS7`](../../pkcs7/) 和 [`PKCS7Detached`](../../pkcs7detached/)。 |

### 另请参见

* class [Signature](../../signature/)
* class [SignatureField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


